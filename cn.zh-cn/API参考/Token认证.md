# Token认证<a name="ZH-CN_TOPIC_0113511423"></a>

## 应用场景<a name="section5608799912249"></a>

当您使用Token认证方式完成认证鉴权时，需要获取用户Token并在调用接口时增加“X-Auth-Token”到业务接口请求消息头中。

本节介绍如何调用接口完成Token认证。

## Token的获取方式<a name="section3546598312249"></a>

1.  发送“POST https://_**IAM的Endpoint**_/v3/auth/tokens”获取Token。

    其中，IAM的Endpoint请参考[地区和终端节点](http://developer.huaweicloud.com/dev/endpoint)。

    请求消息体中的project的id的获取方式请参考 “[获取项目编号](获取项目编号.md)”。

    请求内容示例如下：

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   下面示例代码中的斜体字需要替换为实际内容，详情请参考《_统一身份认证服务API参考_》。  
    >-   获取token后，请执行**history -c**命令，清除记录。  

    ```
    {	
       "auth": {
    	"identity": {
    	    "methods": ["password"],
    		"password": {
    		    "user": {
    			"name": "username",
    			"password": "password",
    			"domain": {
    			    "name": "domainname"
    			}
    		    } 
    		}
    	    },
            "scope": {
                project": {
    	        "id": "0215ef11e49d4743be23dd97a1561e91"//假设id是"0215ef11e49d4743be23dd97a1561e91"
    	    }		
             }	
         }
    }
    ```

2.  <a name="li2615608112249"></a>获取Token，请参考《_统一身份认证服务API参考_》的“获取用户Token”章节。请求响应成功后在响应消息头中包含的“X-Subject-Token”的值即为Token值。
3.  调用业务接口，在请求消息头中增加“X-Auth-Token”，“X-Auth-Token”的取值为[2](#li2615608112249)中获取的Token。

