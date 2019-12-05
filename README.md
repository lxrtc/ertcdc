eRTCDC - Embedded implement for webrtc-datachannel
=================================================
<br/><br/>
一个轻量级的webrtc-datachannel实现，使用纯C语言实现，可被高级语言如C#/Java等集成，也可运行于资源受限的嵌入式设备。<br/>A lightweight implement for webrtc-datachannel, written in pure c, you can use with c# or java and also run in resource-constrained device.
<br/><br/>
借鉴自librtcdc项目，并准备做一些改造（主要是想排除glib等依赖，以及更更深度的集成和解耦；例如把mbedtls/ice以源码形式引用进来并更名以屏蔽全局变量名称）。<br/>Is inspired in no small part by [librtcdc](https://github.com/xhs/librtcdc), but want to do some extra work. Such as exclude dependence of glib, or include ice/mbedtls by Source-Code style.
<br/><br/>
现在项目出于启动和改造时期，请勿用于任何项目，当发布Release时才可用。<br/>Now the project just startup, please wait for a Release pub.
