hostname = *.amemv.com, *.iydsj.com, *.k.sohu.com, *.kakamobi.cn, *.kingsoft-office-service.com, *.meituan.net, *.musical.ly, *.ofo.com, *.pstatp.com, *.snssdk.com, *.tiktokv.com, *.tv.sohu.com, *.uve.weibo.com, *.ydstatic.com, 101.201.175.228, 115.159.231.79, 119.18.193.135, 123.59.31.1, 154.8.131.171, 182.92.251.113, 4gimg.map.qq.com, a.apicloud.com, a.qiumibao.com, acs.m.taobao.com, act.vip.iqiyi.com, api*.futunn.com, api.21jingji.com, api.caijingmobile.com, api.chelaile.net.cn, api.daydaycook.com.cn, api.douban.com, api.gotokeep.com, api.haohaozhu.cn, api.huomao.com, api.intsig.net, api.izuiyou.com, api.jr.mi.com, api.jxedt.com, api.kkmh.com, api.m.jd.com, api.meipian.me, api.mgzf.com, api.psy-1.com, api.qbb6.com, api.rr.tv, api.smzdm.com, api.vistopia.com.cn, api.waitwaitpay.com, api.wallstreetcn.com, api.weibo.cn, api.xiachufang.com, api.xueqiu.com, api.yangkeduo.com, api.zhihu.com, api.zhuishushenqi.com, api-mifit*.huami.com, api-release.wuta-cam.com, app.58.com, app.api.ke.com, app.bilibili.com, app.mixcapp.com, app.poizon.com, app.variflight.com, app.wy.guahao.com, app.xinpianchang.com, app.yinxiang.com, app.zhuanzhuan.com, appapi.huazhu.com, app-api.smzdm.com, appconf.mail.163.com, appv6.55haitao.com, b.zhuishushenqi.com, business-cdn.shouji.sogou.com, c.m.163.com, cap.caocaokeji.cn, capi.mwee.cn, ccsp-egmas.sf-express.com, cdn.moji.com, cdnfile1.msstatic.com, channel.beitaichufang.com, client.mail.163.com, clientaccess.10086.cn, cms.daydaycook.com.cn, consumer.fcbox.com, creditcardapp.bankcomm.com, daoyu.sdo.com, dl.app.gtja.com, dsa-mfp.fengshows.cn, dxy.com, e.dangdang.com, easyreadfs.nosdn.127.net, g.cdn.pengpengla.com, gateway.shouqiev.com, guide-acs.m.taobao.com, gw.alicdn.com, gw.csdn.net, gw-passenger.01zhuanche.com, heic.alicdn.com, i.ys7.com, iapi.bishijie.com, iface.iqiyi.com, ih2.ireader.com, imeclient.openspeech.cn, img.jiemian.com, img01.10101111cdn.com, interface.music.163.com, ios.lantouzi.com, ios.wps.cn, jump2.bdimg.com, kaola-haitao.oss.kaolacdn.com, learn.chaoxing.com, list-app-m.i4.cn, m*.amap.com, m.client.10010.com, m.ibuscloud.com, m.tuniu.com, m.yap.yahoo.com, manga.bilibili.com, mapi.mafengwo.cn, media.qyer.com, mlife.jf365.boc.cn, mob.mddcloud.com.cn, mobi.360doc.com, mp.weixin.qq.com, mrobot.pcauto.com.cn, mrobot.pconline.com.cn, ms.jr.jd.com, msspjh.emarbox.com, news.ssp.qq.com, newsso.map.qq.com, nnapp.cloudbae.cn, open.qyer.com, p.du.163.com, pan.baidu.com, pic*.chelaile.net, pic1cdn.cmbchina.com, pocketuni.net, portal-xunyou.qingcdn.com, promo.xueqiu.com, pss.txffp.com, r.inews.qq.com, render.alipay.com, res.xiaojukeji.com, resrelease.wuta-cam.com, restapi.iyunmai.com, richmanapi.jxedt.com, rtbapi.douyucdn.cn, s*.zdmimg.com, s.youtube.com, service.4gtv.tv, slapi.oray.net, smkmp.96225.com, snailsleep.net, ss0.bdstatic.com, ssl.kohsocialapp.qq.com, static.vuevideo.net, static1.keepcdn.com, status.boohee.com, support.you.163.com, thor.weidian.com, tieba.baidu.com, tiku.zhan.com, weibointl.api.weibo.cn, www.bodivis.com.cn, www.dandanzan.com, www.flyertea.com, www.hxeduonline.com, www.icourse163.org, www.iyingdi.cn, www.tieba.com, www.youtube.com, www.zhihu.com, www.zybang.com, xyz.cnki.net, xyst.yuanfudao.com, youtubei.googleapis.com, yxyapi*.drcuiyutao.com, zhidao.baidu.com


# header-rewrite
# 百度贴吧
^https?+:\/\/(?:c\.)?+tieba\.baidu\.com\/(?>f|p) url request-header (\r\n)User-Agent:.+ request-header $1User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.4 Safari/605.1.15
^https?+:\/\/jump2\.bdimg\.com\/(?>f|p) url request-header (\r\n)User-Agent:.+ request-header $1User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.4 Safari/605.1.15
# 百度知道
^https?+:\/\/zhidao\.baidu\.com url request-header (\r\n)User-Agent:.+ request-header $1User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.4 Safari/605.1.15
# 知乎
^https?+:\/\/www\.zhihu\.com\/question url request-header (\r\n)User-Agent:.+ request-header $1User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/13.0.4 Safari/605.1.15


# url-rewrite
# Redirect Google Search Service
^http:\/\/www\.google\.cn url 302 https://www.google.com


# script
# 阿里
^https?+:\/\/amdc\.m\.taobao\.com\/amdc\/mobileDispatch url response-body .+ response-body eyJjYXJyaWVyIjoiIiwiY2xpZW50SXNwIjoiIiwiY29kZSI6MTAwMCwiY3YiOjEsImRucyI6W3siYWlzbGVzIjpbXSwiaG9zdCI6IiIsImlwcyI6W10sInN0cmF0ZWdpZXMiOltdLCJ0dGwiOjMwMH1dLCJpcCI6IiIsInVpZCI6IiIsInVuaXQiOiIifQ==
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimama\.etao\.config\.query\/ url response-body "ems_etao_advertise" response-body ""


# Tide.list
# Strong Stain Removal
# 0~9
# > 21经济
^https?+:\/\/api\.21jingji\.com\/ad\/ url reject-200
# > 360doc
^https?+:\/\/mobi\.360doc\.com\/v\d{2}\/Ajax\/festival\.ashx\?op=getfestivaltheme url reject-200
# > 55海淘
^https?+:\/\/appv6\.55haitao\.com\/IflyAd\/getAd url reject-200
# > 58同城
^https?+:\/\/app\.58\.com\/api\/home\/a(?>dvertising|ppadv)\/ url reject-200
^https?+:\/\/app\.58\.com\/api\/home\/invite\/popupAdv url reject-200
^https?+:\/\/app\.58\.com\/api\/log\/ url reject-200
^https?+:\/\/.+?\.58cdn\.com\.cn\/brandads\/ url reject-200

# A
# > 阿里
^https?+:\/\/guide-acs\.m\.taobao\.com\/gw\/mtop\.tmall\.wireless url reject-200
# >> 1688
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alibaba\.advertisementservice\.getadv url reject-200
# >> 飞猪
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.trip\.activity\.querytmsresources\/ url reject-200
# >> 淘宝
^https?+:\/\/(?>heic|gw)\.alicdn\.com\/tfs\/TB1.+?-\d{4}-\d{4}\.jpg_1200x1200q90\.jpg_\.\w{3,4}+$ url reject-200
^https?+:\/\/heic\.alicdn\.com\/tps\/i4\/.+?\.jpg_1200x1200q90\.jpg_\.heic$ url reject-200
^https?+:\/\/gw\.alicdn\.com\/tfs\/.+?\d{4}-\d{4}\/[a-z]{3}$ url reject-200
# >> 淘票票
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.film\.mtopadvertiseapi\.queryadvertise\/ url reject-200
# >> 口碑
^https?+:\/\/render\.alipay\.com\/p\/s\/h5data\/prod\/spring-festival-2019-h5data\/popup-h5data\.json url reject-200
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.o2o\.ad\.gateway\.get\/ url reject-200
# >> 高德地图
^https?+:\/\/m\d\.amap\.com\/ws\/valueadded\/alimama\/splash_screen\/ url reject-200
# >> 天猫
^https?+:\/\/gw\.alicdn\.com\/tfs\/TB1.+?750-\d{4} url reject-200
# >> 优酷
^https?+:\/\/.+?\.mp4\?ccode=0902 url reject-200
^https?+:\/\/.+?\.mp4\?sid= url reject-200
^https?+:\/\/vali\.cp31\.ott\.cibntv\.net\/youku\/.+?\.mp4\?sid= url reject-200
# > AcFun
^https?+:\/\/aes\.acfun\.cn\/s\?adzones url reject-200
# > 爱回收
^https?+:\/\/gw\.aihuishou\.com\/app-portal\/home\/getadvertisement url reject-200
# > 爱思助手
^https?+:\/\/list-app-m\.i4\.cn\/getopfstadinfo\.xhtml url reject-200
# > APICloud
^https?+:\/\/a\.apicloud\.com\/start_page\/ url reject-200

# B
# > 百度
# >> 百度网盘
^https?+:\/\/pan\.baidu\.com\/rest\/2\.0\/pcs\/adx url reject-200
^https?+:\/\/pan\.baidu\.com\/act\/api\/activityentry url reject-200
^https?+:\/\/issuecdn\.baidupcs\.com\/issue\/netdisk\/guanggao\/ url reject-200
# >> 百度贴吧
^https?+:\/\/c\.tieba\.baidu\.com\/c\/s\/splashSchedule url reject-200
^https?+:\/\/c\.tieba\.baidu\.com\/c\/f\/forum\/getAdInfo url reject-200
^https?+:\/\/c\.tieba\.baidu\.com\/\w+?\/\w+?\/(?>sync|newRnSync|mlog) url reject-200
# >> 百度地图
^https?+:\/\/ss0\.bdstatic\.com/.+?_\d{3}_\d{4}\.jpg url reject-200
# >> 爱奇艺
^https?+:\/\/iface\.iqiyi\.com\/api\/getNewAdInfo url reject-200
^https?+:\/\/.+?\/(?>mixer|track2)\? url reject-200
^https?+:\/\/act\.vip\.iqiyi\.com\/interact\/api\/show\.do url reject-200
^https?+:\/\/act\.vip\.iqiyi\.com\/interact\/api\/v2\/show url reject-200
# > 哔哩哔哩
^https?+:\/\/app\.bilibili\.com\/x\/v\d\/splash\/ url reject-200
^https?+:\/\/manga\.bilibili\.com\/twirp\/comic\.v\d\.Comic\/Flash url reject-200
# > 抱抱
^https?+:\/\/www\.myhug\.cn\/ad\/ url reject-200
# > 百词斩
^https?+:\/\/7n\.bczcdn\.com\/launchad\/ url reject-200
# > 贝太厨房
^https?+:\/\/channel\.beitaichufang\.com\/channel\/api\/v\d\/promote\/ios\/start\/page url reject-200
# > 币世界
^https?+:\/\/iapi\.bishijie\.com\/actopen\/advertising\/ url reject-200
# > 贝壳找房
^https?+:\/\/app\.api\.ke\.com\/config\/config\/bootpage url reject-200
# > 薄荷
^https?+:\/\/status\.boohee\.com\/api\/v\d\/app_square\/start_up_with_ad url reject-200

# C
# > CNKI
# >> 手机知网
^https?+:\/\/xyz\.cnki\.net\/resourcev7\/api\/manualpush\/SlidsList$ url reject-200
# > CNTV
^https?+:\/\/cntv\.hls\.cdn\.myqcloud\.com\/.+?\?maxbr=850 url reject-200
^https?+:\/\/asp\.cntv\.myalicdn\.com\/.+?\?maxbr=850 url reject-200
^https?+:\/\/www\.cntv\.cn\/nettv\/adp\/ url reject-200
^https?+:\/\/v\.cctv\.com\/.+?850 url reject-200
# > CSDN
^https?+:\/\/gw\.csdn\.net\/cms-app\/v2\/home_page\/open_advertisement url reject-200
# > 车来了
^https?+:\/\/api\.chelaile\.net\.cn\/adpub\/ url reject-200
^https?+:\/\/api\.chelaile\.net\.cn\/goocity\/advert\/ url reject-200
^https?+:\/\/pic\d\.chelaile\.net\.cn\/adv\/ url reject-200
# > 曹操出行
^https?+:\/\/cap\.caocaokeji\.cn\/advert-bss\/ url reject-200
# > 财经
^https?+:\/\/api\.caijingmobile\.com\/ad(?:vert)?+\/ url reject-200
# > 超级课程表
^https?+:\/\/.+?\/V\d\/splash\/getSplashV\d\.action url reject-200
# > 超级星饭团
^https?+:\/\/g\.cdn\.pengpengla\.com\/starfantuan\/boot-screen-info\/ url reject-200
# > 超星学习通
^https?+:\/\/learn\.chaoxing\.com\/apis\/service\/appConfig\? url reject-200

# D
# > 豆瓣
^https?+:\/\/api\.douban\.com\/v\d\/app_ads\/ url reject-200
# > 斗鱼
^https?+:\/\/rtbapi\.douyucdn\.cn\/japi\/sign\/app\/getinfo url reject-200
# > 当当
^https?+:\/\/mapi\.dangdang\.com\/index\.php\?action=init url reject-200
^https?+:\/\/e\.dangdang\.com\/.+?getDeviceStartPage url reject-200
# > 蛋蛋赞
^https?+:\/\/www\.dandanzan\.com\/res\/gdsefse\.js url reject-200
# > 叨鱼
^https?+:\/\/daoyu\.sdo\.com\/api\/userCommon\/getAppStartAd url reject-200
# > 丁香医生
^https?+:\/\/dxy\.com\/app\/i\/ask\/biz\/feed\/launch url reject-200
# > 嘀嗒出行
^https?+:\/\/res\.xiaojukeji\.com\/resapi\/activity\/getPreloaded url reject-200
^https?+:\/\/res\.xiaojukeji\.com\/resapi\/activity\/getPasMultiNotices url reject-200
^https?+:\/\/capis(?:-slb)?+\.didapinche\.com\/ad\/ url reject-200
^https?+:\/\/www\.didapinche\.com\/app\/adstat\/ url reject-200
# > 电视家
^https?+:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/ad\/ url reject-200
# ＞ 毒
^https?+:\/\/app\.poizon\.com\/api\/v1\/app\/advertisement\/adv\/ url reject-200

# E
# > 艺龙
^https?+:\/\/mobile-api2011\.elong\.com\/ad(?>v|gateway) url reject-200
# > e代驾
^https?+:\/\/pic\.edaijia\.cn\/adsplash\/ url reject-200

# F
# > Foodie
^https?+:\/\/foodie-api\.yiruikecorp\.com\/v\d\/(?>banner|notice)\/overview url reject-200
# > FOTOABLE
^https?+:\/\/cdn\.api\.fotoable\.com\/Advertise\/ url reject-200
# > 飞客茶馆
^https?+:\/\/www\.flyertea\.com\/source\/plugin\/mobile\/mobile\.php\?module=advis url reject-200
# > 飞常准
^https?+:\/\/app\.variflight\.com\/ad\/ url reject-200
^https?+:\/\/app\.variflight\.com\/v\d\/advert\/ url reject-200
# > 凤凰秀
^https?+:\/\/dsa-mfp\.fengshows\.cn\/mfp\/mfpMultipleDelivery\.do\?.+?adunitid url reject-200

# G
# > Google
# >> Youtube
^https?+:\/\/.+?\.googlevideo\.com\/.+?(?>&oad|ctier) url reject-200
^https?+:\/\/\w+?\.youtube\.com\/api\/.+?ad url reject-200
^https?+:\/\/\w+?\.youtube\.com\/p(?>agead|tracking) url reject-200
^https?+:\/\/youtubei\.googleapis\.com\/youtubei\/.+?(?>ad|log)_ url reject-200
# > Gofun
^https?+:\/\/gateway\.shouqiev\.com\/fsda\/app\/bootImage\.json url reject-200
# > 国泰君安
^https?+:\/\/dl\.app\.gtja\.com\/dzswem\/kvController\/.+?\.jpg$ url reject-200

# H
# > 杭州公交
^https?+:\/\/m\.ibuscloud\.com\/v2\/app\/getStartPage url reject-200
# > 杭州市·市民卡
^https?+:\/\/smkmp\.96225\.com\/smkcenter\/ad\/ url reject-200
# > 虎扑
^https?+:\/\/games\.mobileapi\.hupu\.com\/\d\/(?:\d\.){2}\d\/status\/init url reject-200
# > 虎牙
^https?+:\/\/business\.msstatic\.com\/advertiser\/ url reject-200
^https?+:\/\/cdnfile1\.msstatic\.com\/cdnfile\/appad\/resource url reject-200
# > 华住会
^https?+:\/\/appapi\.huazhu\.com:\d{4}\/client\/app\/getAppStartPage\/ url reject-200
# > 韩剧社
^https?+:\/\/47\.97\.20\.12\/ad\/ url reject-200
# > 火猫
^https?+:\/\/api\.huomao\.com\/channels\/loginAd url reject-200
# > HiveBox
^https?+:\/\/consumer\.fcbox\.com\/v\d\/ad\/ url reject-200
# > 好好住
^https?+:\/\/api\.haohaozhu\.cn\/index\.php\/home\/AppInit\/getStartPhoto url reject-200
# > 花生地铁
^https?+:\/\/cmsapi\.wifi8\.com\/v\d\/(?>emptyAd|adNew)\/ url reject-200

# I
# > 讯飞
^https?+:\/\/imeclient\.openspeech\.cn\/adservice\/ url reject-200
# > 好体知
^https?+:\/\/www\.bodivis\.com\.cn\/app\/splashAdvertise url reject-200

# J
# > 京东
^https?+:\/\/api\.m\.jd\.com\/client\.action\?functionId=start$ url reject-200
^https?+:\/\/b?dsp-x\.jd\.com\/adx\/ url reject-200
^https?+:\/\/ms\.jr\.jd\.com\/gw\/generic\/base\/na\/m\/adInfo url reject-200
^https?+:\/\/ms\.jr\.jd\.com\/gw\/generic\/aladdin\/na\/m\/getLoadingPicture url reject-200
# > 界面新闻
^https?+:\/\/img\.jiemian\.com\/ads\/ url reject-200
# > 驾校一点通
^https?+:\/\/api\.jxedt\.com\/ad\/ url reject-200
^https?+:\/\/richmanapi\.jxedt\.com\/api\/ad\/ url reject-200
# > 驾考宝典
^https?+:\/\/.+?\.kakamobi\.cn\/api\/open\/v\d\/advert-sdk\/ url reject-200
# > 金山 WPS
^https?+:\/\/ios\.wps\.cn\/ad-statistics-service url reject-200
^https?+:\/\/mobile-pic\.cache\.iciba\.com\/feeds_ad\/ url reject-200
^https?+:\/\/\w+?\.kingsoft-office-service\.com\/ad url reject-200
# > 金山词霸
^https?+:\/\/dict-mobile\.iciba\.com\/interface\/index\.php\?.+?(?>c=ad|collectFeedsAdShowCount|KSFeedsAdCardViewController) url reject-200
^https?+:\/\/service\.iciba\.com\/popo\/open\/screens\/v\d\?adjson url reject-200

# K
# > Keep
^https?+:\/\/api\.gotokeep\.com\/ads url reject-200
^https?+:\/\/static1\.keepcdn\.com\/.+?\d{3}x\d{4} url reject-200
# > 快递100
^https?+:\/\/p\.kuaidi100\.com\/mobile\/mobileapi\.do url reject-200
# > 快看漫画
^https?+:\/\/api\.kkmh\.com\/.+?ad(?:vertisement)?+\/ url reject-200
# > 酷我 (122.14.246.33,175.102.178.52)
^https?+:\/\/(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/MobileAdServer\/ url reject-200
^https?+:\/\/(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/EcomResourceServer\/AdPlayPage\/adinfo url reject-200
# > 看理想
^https?+:\/\/api\.vistopia\.com\.cn\/api\/v\d\/home\/advertisement url reject-200

# L
# > 乐视
^https?+:\/\/.+?\/letv-gug\/ url reject-200
# > 来疯直播
^https?+:\/\/api\.laifeng\.com\/v\d\/start\/ads url reject-200
# > 懒投资
^https?+:\/\/ios\.lantouzi\.com\/api\/startpage url reject-200
# > 旅法师营地
^https?+:\/\/www\.iyingdi\.cn\/ad url reject-200

# M
# > 小米
^https?+:\/\/api\.m\.mi\.com\/v\d\/app\/start url reject-200
^https?+:\/\/api\.jr\.mi\.com\/v\d\/adv\/ url reject-200
^https?+:\/\/api\.jr\.mi\.com\/jr\/api\/playScreen url reject-200
^https?+:\/\/api-mifit.+?\.huami\.com\/discovery\/mi\/discovery\/.+?_ad\? url reject-200
# > 蘑菇租房
^https?+:\/\/api\.mgzf\.com\/renter-operation\/home\/startHomePage url reject-200
# > 墨迹天气
^https?+:\/\/cdn\.moji\.com\/ad(?>oss|link)\/ url reject-200
# > 埋堆堆
^https?+:\/\/mob\.mddcloud\.com\.cn\/api\/ad(?:vert)?+\/ url reject-200
# > 漫画人
^https?+:\/\/mangaapi\.manhuaren\.com\/v\d\/public\/getStartPageAds url reject-200
# > 美团
^https?+:\/\/img\.meituan\.net\/(?>adunion|display|midas)\/.+?\.(gif|jpg|jpg\.webp)$ url reject-200
^https?+:\/\/p\d\.meituan\.net\/wmbanner\/[A-Za-z0-9]+?\.jpg url reject-200
^https?+:\/\/p\d\.meituan\.net\/movie\/[A-Za-z0-9]+?\.jpg\?may_covertWebp url reject-200
^https?+:\/\/s3plus\.meituan\.net\/.+?\/linglong\/.+?\.(?>gif|jpg|mp4) url reject-200
# > 美味不用等
^https?+:\/\/capi\.mwee\.cn\/app-api\/V\d{2}\/app\/(?:getstart)?+ad url reject-200
# > 秒拍
^https?+:\/\/b-api\.ins\.miaopai\.com\/\d\/ad/ url reject-200
# > 马蜂窝
^https?+:\/\/mapi\.mafengwo\.cn\/ad\/ url reject-200
^https?+:\/\/mapi\.mafengwo\.cn\/travelguide\/ad\/ url reject-200
# > 买单吧
^https?+:\/\/creditcardapp\.bankcomm\.com\/mapp\/common\/queryGuidePageAds\.do$ url reject-200
^https?+:\/\/creditcardapp\.bankcomm\.com\/mapp\/common\/getPopAds\.do$ url reject-200
# > 美篇
^https?+:\/\/api\.meipian\.me.+?advert url reject-200

# N
# > 爱南宁
^https?+:\/\/nnapp\.cloudbae\.cn\/mc\/api\/advert url reject-200
# > NationalGeographic
^https?+:\/\/dili\.bdatu\.com\/jiekou\/ad\/ url reject-200
# > NationalGeographicChina
^https?+:\/\/wap\.ngchina\.cn\/news\/adverts\/ url reject-200

# O
# > ofo
^https?+:\/\/supportda\.ofo\.com\/adaction\? url reject-200
^https?+:\/\/ma\.ofo\.com\/ads\/ url reject-200
^https?+:\/\/activity2\.api\.ofo\.com\/ofo\/Api\/v2\/ads url reject-200
^https?+:\/\/ma\.ofo\.com\/adImage\/ url reject-200
# > Oray
^https?+:\/\/slapi\.oray\.net\/client\/ad url reject-200

# P
# > PU口袋校园
^https?+:\/\/pocketuni\.net\/\?app=api&mod=Message&act=ad url reject-200
# > 票根
^https?+:\/\/pss\.txffp\.com\/piaogen\/images\/launchScreen url reject-200
# > 拼多多
^https?+:\/\/api\.yangkeduo\.com\/api\/cappuccino\/splash url reject-200

# Q
# > Qdaily
^https?+:\/\/app\d\.qdaily\.com\/app\d\/boot_advertisements\.json url reject-200
^https?+:\/\/notch\.qdaily\.com\/api\/v\d\/boot_ad url reject-200
# > 穷游
^https?+:\/\/open\.qyer\.com\/qyer\/startpage\/ url reject-200
^https?+:\/\/open\.qyer\.com\/qyer\/config\/get url reject-200
^https?+:\/\/media\.qyer\.com\/ad\/ url reject-200
# > 亲宝宝
^https?+:\/\/api\.qbb6\.com\/ad\/ url reject-200

# R
# > 人人视频
^https?+:\/\/msspjh\.emarbox\.com\/getAdConfig url reject-200
^https?+:\/\/api\.videozhishi\.com\/api\/getAdvertising url reject-200
^https?+:\/\/api\.rr\.tv\/ad\/ url reject-200
# > 日日煮
^https?+:\/\/api\.daydaycook\.com\.cn\/daydaycook\/server\/ad\/ url reject-200
^https?+:\/\/cms\.daydaycook\.com\.cn\/api\/cms\/advertisement\/ url reject-200

# S
# > 扫描全能王
^https?+:\/\/api\.intsig\.net\/user\/cs\/operating\/app\/get_startpic\/ url reject-200
# > 什么值得买
^https?+:\/\/api\.smzdm\.com\/v\d\/util\/loading url reject-200
^https?+:\/\/app-api\.smzdm\.com\/util\/loading url reject-200
^https?+:\/\/s\d\.zdmimg\.com\/www\/api\/v\d\/api\/thirdAd\.php url reject-200
# > 神舟专车
^https?+:\/\/img01\.10101111cdn\.com\/adpos\/ url reject-200
# > 省点
^https?+:\/\/api\.waitwaitpay\.com\/\/api\/splash url reject-200
# > 识货
^https?+:\/\/www\.shihuo\.cn\/app\d\/saveAppInfo url reject-200
# > 首汽约车
^https?+:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/car-rest\/webservice\/passenger\/recommendADs url reject-200
^https?+:\/\/gw-passenger\.01zhuanche\.com\/gw-passenger\/zhuanche-passenger-token\/leachtoken\/webservice\/homepage\/queryADs url reject-200
# > 顺丰速运
^https?+:\/\/ccsp-egmas\.sf-express\.com\/cx-app-base\/base\/app\/ad\/queryAdImages url reject-200
# > 四季線上影視4gTV
^https?+:\/\/service\.4gtv\.tv\/4gtv\/Data\/(?>GetAD|ADLog) url reject-200
# > 肆客足球
^https?+:\/\/api\.qiuduoduo\.cn\/guideimage url reject-200
# > 搜狗
^https?+:\/\/business-cdn\.shouji\.sogou\.com\/wapdl\/hole\/.+?\.jpg url reject-200
# > 搜狐
^https?+:\/\/api\.k\.sohu\.com\/api\/news\/adsense url reject-200
^https?+:\/\/pic\.k\.sohu\.com\/img8\/wb\/tj\/ url reject-200
^https?+:\/\/s1\.api\.tv\.itc\.cn\/v4\/mobile\/control\/switch\.json url reject-200
^https?+:\/\/api\.tv\.sohu\.com\/agg\/api\/app\/config\/bootstrap url reject-200
# > 苏宁
^https?+:\/\/image\.suning\.cn\/uimg\/ma\/ad\/ url reject-200

# T
# > 腾讯
# >> 富途牛牛
^https?+:\/\/api\d\.futunn\.com\/ad\/ url reject-200
# >> 全民K歌
^https?+:\/\/y\.gtimg\.cn\/music\/common\/\/upload\/kg_ad\/.+?\d{3,4}+x\d{4} url reject-200
# >> 腾讯游戏
^https?+:\/\/ssl\.kohsocialapp\.qq\.com:10001\/game\/buttons url reject-200
^https?+:\/\/qt\.qq\.com\/lua\/mengyou\/get_splash_screen_info url reject-200
# >> 腾讯地图
^https?+:\/\/3gimg\.qq\.com\/tencentMapTouch\/app\/activity\/ url reject-200
^https?+:\/\/3gimg\.qq\.com\/tencentMapTouch\/splash\/ url reject-200
^https?+:\/\/4gimg\.map\.qq\.com\/mwaSplash\/ url reject-200
# >> 腾讯视频
^https?+:\/\/vv\.video\.qq\.com\/getvmind\? url reject-200
^https?+:\/\/(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/.+?\.tc\.qq\.com\/.+?p201\.1\.mp4\? url reject-200
# >> 腾讯新闻
^https?+:\/\/r\.inews\.qq\.com\/(?>adsBlacklist|getFullScreenPic|getQQNewsRemoteConfig) url reject-200
# >> 腾讯体育
^https?+:\/\/news\.ssp\.qq\.com\/app url reject-200
# >> JOOX
^https?+:\/\/203\.205\.255\.16\/retrieval\/getAd url reject-200
^https?+:\/\/hk\.app\.joox\.com\/billsrv\/clientBatchAdReport url reject-200
^https?+:\/\/hk\.app\.joox\.com\/retrieval\/getAd url reject-200
^https?+:\/\/smusic\.app\.wechat\.com\/commonCgi\/advertisement\/get_orint_egg$ url reject-200
^https?+:\/\/smusic\.app\.wechat\.com\/fcgi-bin\/get_(?>a|i) url reject-200
^https?+:\/\/tiasdk\.app\.wechat\.com\/retrieval\/getAdInfo$ url reject-200
^https?+:\/\/mm\.app\.joox\.com\/retrieval\/getAd url reject-200
^https?+:\/\/mm\.app\.joox\.com\/billsrv\/clientBatchAdReport$ url reject-200
# >> 微信
^https?+:\/\/mp\.weixin\.qq\.com\/mp\/(?>ad_|advertisement|getappmsgad) url reject-200
# > 澎湃新闻
^https?+:\/\/adpai\.thepaper\.cn\/.+?&ad= url reject-200
# > 太平洋
^https?+:\/\/agent-count\.pconline\.com\.cn\/counter\/adAnalyse\/ url reject-200
^https?+:\/\/mrobot\.pconline\.com\.cn\/v\d\/ad2p url reject-200
^https?+:\/\/mrobot\.pconline\.com\.cn\/s\/onlineinfo\/ad\/ url reject-200
^https?+:\/\/mrobot\.pcauto\.com\.cn\/v\d\/ad2p url reject-200
^https?+:\/\/mrobot\.pcauto\.com\.cn\/xsp\/s\/auto\/info\/preload\.xsp url reject-200
# > 途牛
^https?+:\/\/m\.tuniu\.com\/api\/operation\/splash\/ url reject-200

# V
# > VUE
^https?+:\/\/static\.vuevideo\.net\/styleAssets\/.+?\/splash_ad url reject-200
^https?+:\/\/static\.vuevideo\.net\/styleAssets\/advertisement\/ url reject-200

# W
# > 网易
# >> 网易邮箱
^https?+:\/\/appconf\.mail\.163\.com\/mmad\/ url reject-200
# >> 网易新闻
^https?+:\/\/c\.m\.163\.com\/nc\/gl\/ url reject-200
# >> 网易有钱
^https?+:\/\/client\.mail\.163\.com\/apptrack\/confinfo\/searchMultiAds url reject-200
# >> 网易云音乐
^https?+:\/\/.+?\/eapi\/(?>ad|log)\/ url reject-200
# >> 网易考拉
^https?+:\/\/kaola-haitao\.oss\.kaolacdn.com\/.+?_\d{3,4}+_\d{4}\.jpg\?x-oss-process=image\/resize,m_mfit,w_\d{3,4}+,h_\d{4}\/format,webp\/quality,Q_85 url reject-200
# >> 网易严选
^https?+:\/\/support\.you\.163\.com\/xhr\/boot\/getBootMedia\.json url reject-200
# >> 网易蜗牛读书
^https?+:\/\/easyreadfs\.nosdn\.127\.net\/ad-material\/ url reject-200
^https?+:\/\/p\.du\.163\.com\/ad\/ url reject-200
# >> 有道词典
^https?+:\/\/oimage[a-z][0-9]\.ydstatic\.com\/.+?adpublish url reject-200
^https?+:\/\/dsp-impr2\.youdao\.com\/adload url reject-200
# > 微医
^https?+:\/\/app\.wy\.guahao\.com\/json\/white\/dayquestion\/getpopad url reject-200
# > Weico
^https?+:\/\/overseas\.weico\.cc\/portal\.php\?a=get_coopen_ads url reject-200
# > 无他相机
^https?+:\/\/api-release\.wuta-cam\.com\/ad_tree url reject-200
^https?+:\/\/res-release\.wuta-cam\.com\/json\/ads_component_cache\.json url reject-200
# > 蜗牛睡眠
^https?+:\/\/snailsleep\.net\/snail\/v\d\/screen\/qn\/get\? url reject-200
^https?+:\/\/snailsleep\.net\/snail\/v\d\/adTask\/ url reject-200
# > WiFi共享大师
^https?+:\/\/nochange\.ggsafe\.com\/ad\/ url reject-200
# > 微店
^https?+:\/\/thor\.weidian\.com\/ares\/home\.splash\/ url reject-200
# > 华尔街见闻
^https?+:\/\/api\.wallstreetcn\.com\/apiv\d\/advertising\/ url reject-200

# X
# > 新浪
^https?+:\/\/edit\.sinaapp\.com\/ua\?t=adv url reject-200
# >> 新浪微博
^https?+:\/\/sdkapp\.uve\.weibo\.com\/interface\/sdk\/(?>action|sdk)ad\.php url reject-200
^https?+:\/\/wbapp\.uve\.weibo\.com\/wbapplua\/wbpullad\.lua url reject-200
^https?+:\/\/weibointl\.api\.weibo\.cn\/portal\.php\?a=get_coopen_ads url reject-200
# >> 新浪天气通
^https?+:\/\/tqt\.weibo\.cn\/overall\/redirect\.php\?r=tqt url reject-200
^https?+:\/\/tqt\.weibo\.cn\/.+?advert\.index url reject-200
^https?+:\/\/tqt\.weibo\.cn\/api\/advert\/ url reject-200
# > 下厨房
^https?+:\/\/api\.xiachufang\.com\/v\d\/ad\/ url reject-200
# > 虾米
^https?+:\/\/acs\.m\.taobao\.com\/gw\/mtop\.alimusic\.common\.mobileservice\.startinit\/ url reject-200
# > 小睡眠
^https?+:\/\/api\.psy-1\.com\/cosleep\/startup url reject-200
# > 小猿搜题
^https?+:\/\/xyst\.yuanfudao\.com\/iphone\/splashesV\d url reject-200
# > 新片场
^https?+:\/\/app\.xinpianchang\.com\/open_screen\? url reject-200
# > 雪球
^https?+:\/\/api\.xueqiu\.com\/ads\/display url reject-200
^https?+:\/\/(?>promo|api)\.xueqiu\.com\/promotion\/(?:feed_)?+display url reject-200
^https?+:\/\/(?>101\.201\.175\.228|182\.92\.251\.113)\/promotion\/(?:feed_)?+display url reject-200
# > 迅游加速器
^https?+:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/configs\/(?>splash_ad|ad_urls) url reject-200
^https?+:\/\/portal-xunyou\.qingcdn\.com\/api\/v\d\/ios\/ads\/ url reject-200
# > 喜马拉雅
^https?+:\/\/\w+?\.ximalaya\.com\/api\/v\d\/adRealTime url reject-200
^https?+:\/\/(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]?\d)\/ting\/preload\/ url reject-200
# > 小站
^https?+:\/\/tiku\.zhan\.com\/Common\/newAd\/ url reject-200

# Y
# > Yahoo!
^https?+:\/\/m\.yap\.yahoo\.com\/v\d{2}\/getAds\.do url reject-200
# > Youtube++
^https?+:\/\/api\.catch\.gift\/api\/v\d\/pagead\/ url reject-200
# > 萤石云视频
^https?+:\/\/i\.ys7\.com\/api\/ads url reject-200
# > 阅达教育
^https?+:\/\/www\.hxeduonline\.com\/mobileapi2\/index\.php\?act=index&op=interdict url reject-200
# > 运动世界
^https?+:\/\/.+?\.iydsj\.com\/api\/.+?\/ad url reject-200
# > 一点万象
^https?+:\/\/app\.mixcapp\.com\/mixc\/api\/v\d\/ad url reject-200
# > 印象笔记
^https?+:\/\/app\.yinxiang\.com\/ads\/ url reject-200
# > 云麦好轻
^https?+:\/\/restapi\.iyunmai\.com\/api\/ios\/ad\/ url reject-200
# > 育学园
^https?+:\/\/yxyapi\d\.drcuiyutao\.com\/yxy-api-gateway\/api\/json\/advert\/ url reject-200
# > 迅雷
^https?+:\/\/images\.client\.vip\.xunlei\.com\/.+?\/advert\/ url reject-200
# > 讯飞
^https?+:\/\/imeclient\.openspeech\.cn\/adservice\/ url reject-200

# Z
# > 转转
^https?+:\/\/app\.zhuanzhuan\.com\/zzx\/transfer\/getConfigInfo$ url reject-200
# > 直播吧
^https?+:\/\/a\.qiumibao\.com\/activities\/config\.php url reject-200
^https?+:\/\/.+?\/allOne\.php\?ad_name url reject-200
# > 知乎
^https?+:\/\/api\.zhihu\.com\/(?>launch|real_time) url reject-200
^https?+:\/\/api\.zhihu\.com\/commercial_api\/(?>launch|real_time) url reject-200
^https?+:\/\/api\.zhihu\.com\/fringe\/ad url reject-200
^https?+:\/\/api\.zhihu\.com\/(?>ab|adx|xen|drama|zst|ad-style-service|market\/popover|search\/(?>top|tab|preset)|.*?(?>guide|recommendations|extended|featured-comment-ad)) url reject-200
^https?+:\/\/www\.zhihu\.com\/api\/v4\/cmmunity-ad url reject-200
# > 追书神器
^https?+:\/\/(?>api|b)\.zhuishushenqi\.com\/advert url reject-200
^https?+:\/\/api\.zhuishushenqi\.com\/splashes\/ios url reject-200
^https?+:\/\/api\.zhuishushenqi\.com\/notification\/shelfMessage url reject-200
^https?+:\/\/api\.zhuishushenqi\.com\/user\/bookshelf-updated url reject-200
^https?+:\/\/itunes\.apple\.com\/lookup\?id=575826903 url reject-200
# > 作业帮
^https?+:\/\/www\.zybang\.com\/adx\/ url reject-200
# > 最右
^https?+:\/\/api\.izuiyou\.com\/ad\/ url reject-200
# > 字节跳动
^https?+:\/\/.+?\.pstatp\.com\/img\/ad url reject-200
^https?+:\/\/.+?\.(?>amemv|musical|snssdk|tiktokv)\.(?>com|ly)\/(?>api|motor)\/ad\/ url reject-200
^https?+:\/\/dsp\.toutiao\.com\/api\/xunfei\/ads\/ url reject-200
^https?+:\/\/.+?\.snssdk\.com\/motor\/operation\/activity\/display\/config\/V2\/ url reject-200
^https?+:\/\/.+?\/img\/ad\.union\.api\/ url reject-200
# > 涨乐财富通
^https?+:\/\/d\.zhangle\.com\/pic\/cft\/interaction\/\d{13}-1242-2248\.jpg url reject-200
# > 中国大学慕课
^https?+:\/\/www\.icourse163\.org\/mob\/j\/v1\/mobRecommendRPCBean\.getMaxWeightAdvertisement\.rpc url reject-200
# > 中国银行
^https?+:\/\/mlife\.jf365\.boc\.cn\/AppPrj\/FirstPic\.do\? url reject-200
# > 中国工商银行
^https?+:\/\/v\.icbc\.com\.cn\/userfiles\/Resources\/WAP\/advertisement\/ url reject-200
# > 中国招商银行
^https?+:\/\/pic1cdn\.cmbchina\.com\/appinitads\/ url reject-200
# > 中国民生银行
^https?+:\/\/www\.cmbc\.com\.cn\/m\/image\/loadingpage\/ url reject-200
# > 中国广发银行
^https?+:\/\/mps\.95508\.com\/mps\/club\/cardPortals\/adv\/.{25}\.jpg url reject-200
# > 中国移动
# >> 手机营业厅
^https?+:\/\/clientaccess\.10086\.cn\/biz-orange\/DN\/init\/startInit url reject-200
# >> 江苏
^https?+:\/\/wap\.js\.10086\.cn\/jsmccClient\/cd\/market_content\/api\/v\d\/market_content\.page\.query url reject-200
# >> 咪咕
^https?+:\/\/gg\w+?\.cmvideo\.cn\/v\d\/iflyad\/ url reject-200
^https?+:\/\/ggic\d?\.cmvideo\.cn\/ad\/ url reject-200
^https?+:\/\/ggx\.cmvideo\.cn\/request\/ url reject-200
^https?+:\/\/.+?\/cdn-adn\/ url reject-200
# > 中国联通
^https?+:\/\/m\.client\.10010\.com\/mobileService\/customer\/accountListData\.htm url reject-200
^https?+:\/\/m\.client\.10010\.com\/uniAdmsInterface\/getWelcomeAd url reject-200
# > 掌阅
^https?+:\/\/ih2\.ireader\.com\/zyapi\/bookstore\/ad\/ url reject-200
^https?+:\/\/ih2\.ireader\.com\/zyapi\/self\/screen\/ad url reject-200
^https?+:\/\/ih2\.ireader\.com\/zycl\/api\/ad\/ url reject-200
