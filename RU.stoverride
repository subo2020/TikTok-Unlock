名称：TikTok解锁-俄罗斯
desc: 锁定地区限制，建议使用Tiktok21.1.10版本

网址：
  中间人：
    - “*.tiktokv.com”
    - “*.byteoversea.com”
    - “*.tik-tokapi.com”
  改写：
    - (?<=_region=)CN(?=&) RU 307
    - (?<=&mcc_mnc=)4 2 307
    - ^(https?:\/\/(tnc|dm)[\w-]+\.\w+\.com\/.+)(\?)(.+) $1$3 302
    - (^https?:\/\/*\.\w{4}okv.com\/.+&.+)(\d{2}\.3\.\d)(.+) $118.0$3 302
