# captcha-killer-java8
`captcha-killer`要解决的问题是让burp能用上各种验证码识别技术。

换到burp2020后，这款工具就用不了了，因为原工具Base64编码是使⽤JDK⾥sun.misc套件下的BASE64Encoder和BASE64Decoder这两个类，但是burp2020只能运行在java8环境下，JDK1.8已经取消了这个编码方法，所以burp2020就用不了这个插件了。

因为平时渗透测试，用到验证码爆破的场景挺多的，而且又想体验新版burp，所以就花了点时间改了源码重新编译了一下


原工具地址：https://github.com/c0ny1/captcha-killer
