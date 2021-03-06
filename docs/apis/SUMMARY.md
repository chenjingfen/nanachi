# API

- [概述](index.md#概述)
- [网络](network.md#网络)
  - [request](network.md#request)
  - [uploadFile](network.md#uploadfileobject-object)
  - [downloadFile](network.md#downloadfileobject-object)
  - [connectSocket](network.md#connectsocketobject-object)
  - [onSocketOpen](network.md#onsocketopenfunction-callback)
  - [closeSocket](network.md#closesocketobject-object)
  - [sendSocketMessage](network.md#sendsocketmessageobject-object)
  - [onSocketMessage](network.md#onsocketmessagefunction-callback)
  - [onSocketError](network.md#onsocketerrorfunction-callback)
  - [onSocketClose](network.md#onsocketclosefunction-callback)
- [交互](interaction.md#交互)
  - [showModal](interaction.md#showmodalobject-object)
  - [showToast](interaction.md#showtoastobject-object)
  - [hideToast](interaction.md#hidetoast)
  - [showLoading](interaction.md#showloadingobject-object)
  - [hideLoading](interaction.md#hideloading)
  - [showActionSheet](interaction.md#showactionsheetobject-object)
- [导航](nav.md#导航)
  - [navigateTo](nav.md#navigatetoobject)
  - [redirectTo](nav.md#redirecttoobject)
  - [reLaunch](nav.md#relaunchobject)
  - [navigateBack](nav.md#navigatebackobject)
- [设置导航条](nav.md#设置导航条)
  - [setNavigationBarTitle](nav-bar.md#setnavigationbartitleobject)
  - [setNavigationBarColor](nav-bar.md#setnavigationbarcolorobject)
  - [showNavigationBarLoading](nav-bar.md#shownavigationbarloading)
  - [hideNavigationBarLoading](nav-bar.md#hidenavigationbarloading)
- [TabBar](api.md#TabBar)
  - [switchTab](api.md#tabbar-switchtabobject)
- [动画](animation.md#动画)
  - [createAnimation](animation.md#createanimationobject-object)
  - [animation](animation.md#animation)
- [画布](canvas.md#画布)
  - [createCanvasContext](canvas.md#createcanvascontextcanvasid)
  - [CanvasContext.setTextAlign](canvas.md#canvascontext.settextalignstring-align)
  - [CanvasContext.setTextBaseline](canvas.md#canvascontext.settextbaselinestring-textbaseline)
  - [CanvasContext.setFillStyle](canvas.md#canvascontext.setfillstylestring-color)
  - [CanvasContext.setStrokeStyle](canvas.md#canvascontext.setstrokestylestring-color)
  - [CanvasContext.setShadow](canvas.md#canvascontext.setshadownumber-offsetx,-number-offsety,-number-blur,-string-color)
  - [CanvasContext.createLinearGradient](canvas.md#canvascontext.createlineargradientnumber-x0,-number-y0,-number-x1,-number-y1)
  - [CanvasContext.createCircularGradient](canvas.md#canvascontext.createcirculargradientnumber-x0,-number-y0,-number-x1,-number-y1)
  - [CanvasGradient.addColorStop](canvas.md#canvasgradient.addcolorstopnumber-stop,-string-color)
  - [CanvasContext.setLineWidth](canvas.md#canvascontext.setlinewidthnumber-linewidth)
  - [CanvasContext.setLineCap](canvas.md#canvascontext.setlinecapstring-linecap)
  - [CanvasContext.setLineJoin](canvas.md#canvascontext.setlinejoinstring-linejoin)
  - [CanvasContext.setMiterLimit](canvas.md#canvascontext.setmiterlimitnumber-miterlimit)
  - [CanvasContext.rect](canvas.md#canvascontext.rectnumber-x,-number-y,-number-width,-number-height)
  - [CanvasContext.fillRect](canvas.md#canvascontext.fillrectnumber-x,-number-y,-number-width,-number-height)
  - [CanvasContext.strokeRect](canvas.md#canvascontext.strokerectnumber-x,-number-y,-number-width,-number-height)
  - [CanvasContext.clearRect](canvas.md#canvascontext.clearrectnumber-x,-number-y,-number-width,-number-height)
  - [CanvasContext.fill](canvas.md#canvascontext.fill)
  - [CanvasContext.stroke](canvas.md#canvascontext.stroke)
  - [CanvasContext.beginPath](canvas.md#canvascontext.beginpath)
  - [CanvasContext.closePath](canvas.md#canvascontext.closepath)
  - [CanvasContext.moveTo](canvas.md#canvascontext.movetonumber-x,-number-y)
  - [CanvasContext.lineTo](canvas.md#canvascontext.linetonumber-x,-number-y)
  - [CanvasContext.arc](canvas.md#canvascontext.arcnumber-x,-number-y,-number-r,-number-sangle,-number-eangle,-number-counterclockwise)
  - [CanvasContext.bezierCurveTo](canvas.md#canvascontext.beziercurveto)
  - [CanvasContext.clip](canvas.md#canvascontext.clip)
  - [CanvasContext.quadraticCurveTo](canvas.md#canvascontext.quadraticcurvetonumber-cpx,-number-cpy,-number-x,-number-y)
  - [CanvasContext.scale](canvas.md#canvascontext.scalenumber-scalewidth,-number-scaleheight)
  - [CanvasContext.rotate](canvas.md#canvascontext.rotatenumber-rotate)
  - [CanvasContext.translate](canvas.md#canvascontext.translatenumber-x,-number-y)
  - [CanvasContext.setFontSize](canvas.md#canvascontext.setfontsizenumber-fontsize)
  - [CanvasContext.fillText](canvas.md#canvascontext.filltextstring-text,-number-x,-number-y,-number-maxwidth)
  - [CanvasContext.drawImage](canvas.md#canvascontext.drawimagestring-imageresource,-number-dx,-number-dy,-number-dwidth,-number-dheight,-number-sx,-number-sy,-number-swidth,-number-sheight)
  - [CanvasContext.setGlobalAlpha](canvas.md#canvascontext.setglobalalphanumber-透明度。范围)
  - [CanvasContext.setLineDash](canvas.md#canvascontext.setlinedasharray.-pattern,-number-offset)
  - [CanvasContext.transform](canvas.md#canvascontext.transformnumber-scalex,-number-skewx,-number-skewy,-number-scaley,-number-translatex,-number-translatey)
  - [CanvasContext.setTransform](canvas.md#canvascontext.settransformnumber-scalex,-number-skewx,-number-skewy,-number-scaley,-number-translatex,-number-translatey)
  - [CanvasContext.save](canvas.md#canvascontext.save)
  - [CanvasContext.restore](canvas.md#canvascontext.restore)
  - [CanvasContext.draw](canvas.md#canvascontext.drawboolean-reserve,-function-callback)
  - [CanvasContext.measureText](canvas.md#object-canvascontext.measuretextstring-text)
  - [CanvasContext.canvastotempfilepathobject](canvas.md#canvascontext.canvastotempfilepathobject,-this)
- [键盘](keyboard.md#键盘)
  - [hideKeyboard](keyboard.md#hidekeyboard)
- [滚动](scroll.md#滚动)
  - [pageScrollTo](scroll.md#pagescrollto)
- [下拉刷新](pulldown.md#下拉刷新)
    - [stopPullDownRefresh](pulldown.md#stopPullDownRefresh)
- [节点查询](select.md#节点查询)
  - [createSelectorQuery](select.md#createselectorquery)
  - [SelectorQuery.select](select.md#nodesref-selectorquery.selectstring-selector)
  - [SelectorQuery.selectAll](select.md#nodesref-selectorquery.selectall)
  - [SelectorQuery.selectViewport](select.md#nodesref-selectorquery.selectviewport)
  - [NodesRef.boundingClientRect](select.md#selectquery-nodesref.boundingclientrectfunction-callback)
  - [NodesRef.scrollOffset](select.md#selectquery-nodesref.scrolloffsetfunction-callback)
  - [SelectorQuery.exec](select.md#nodesref-selectorquery.execfunction-callback)
- [图片](image.md#图片)
  - [chooseImage](image.md#chooseimageobject-object)
  - [previewImage](image.md#previewimageobject-object)
  - [saveImageToPhotosAlbum](image.md#saveimagetophotosalbumobject-object)
  - [getImageInfo](image.md#getimageinfoobject-object)
- [录音管理](recorder.md#录音)
  - [getRecorderManager](recorder.md#getRecorderManager)
- [数据缓存](storage.md#缓存)
  - [setStorage](storage.md#setstorageobject-object)
  - [setStorageSync](storage.md#setstoragesyncstring-key,-object|string-data)
  - [getStorage](storage.md#getstorage)
  - [getstoragesync](storage.md#getstoragesync)
  - [removeStorage](storage.md#removestorageobject-object)
  - [removeStorageSync](storage.md#removestoragesyncstring-key)
  - [clearStorage](storage.md#clearstorageobject-object)
  - [clearStorageSync](storage.md#clearstoragesyncobject-object)
  - [getStorageInfo](storage.md#getstorageinfoobject-object)
  - [getStorageInfoSync](storage.md#getstorageinfosyncobject-object)
- [文件](file.md#文件)
  - [getFileInfo](file.md#getfileinfoobject-object)
  - [getSavedFileInfo](file.md#getsavedfileinfoobject-object)
  - [getSavedFileList](file.md#getsavedfilelistobject-object)
  - [removeSavedFile](file.md#removesavedfileobject-object)
  - [saveFile](file.md#savefileobject-object)
- [位置](location.md#位置)
  - [getLocation](location.md#getlocationobject-object)
  - [openLocation](location.md#openlocationobject-object)
  - [chooseLocation](location.md#chooselocationobject-object)
* [分享](share.md#分享)
  * [onShareAppMessage](share.md#onshareappmessageobject)
  * [hideShareMenu](share.md#hidesharemenuobject-object)
### 设备
* [振动](miniprogram.md#振动)
  * [vibrateLong](miniprogram.md#vibratelongobject-object)
  * [vibrateShort](miniprogram.md#vibrateshortobject-object)
* [电话](miniprogram.md#电话)
  * [makePhoneCall](miniprogram.md#makephonecallobject-object)
* [网络](miniprogram.md#网络)
  * [getNetworkType](miniprogram.md#getnetworktypeobject-object)
  * [onNetworkStatusChange](miniprogram.md#onnetworkstatuschangefunction-callback)
* [剪切板](miniprogram.md#剪切板)
  * [getClipboardData](miniprogram.md#getclipboarddataobject-object)
  * [setClipboardData](miniprogram.md#setclipboarddataobject-object)
* [屏幕](miniprogram.md#屏幕)
  * [setKeepScreenOn](miniprogram.md#setkeepscreenonobject-object)
  * [getScreenBrightness](miniprogram.md#getscreenbrightnessobject-object)
  * [setScreenBrightness](miniprogram.md#setscreenbrightnessobject)
* [系统信息](miniprogram.md#系统信息)
  * [getSystemInfo](miniprogram.md#getsysteminfoobject-object)
  * [getSystemInfoSync](miniprogram.md#getsysteminfosyncobject-object)
* [扫码-需要适配支付宝](miniprogram.md#扫码)
  * [scanCode](miniprogram.md#scancodeobject-object)
* [用户截屏事件](miniprogram.md#用户截屏事件)
  * [onUserCaptureScreen](miniprogram.md#onusercapturescreenobject-object)
* [canIUse](miniprogram.md#boolean-caniusestring-schema)
* [iBeacon](iBeacon.md#iBeacon)
  * [startBeaconDiscovery](iBeacon.md#startbeacondiscoveryobject)
  * [stopBeaconDiscovery](iBeacon.md#stopbeacondiscoveryobject)
  * [getBeacons](iBeacon.md#getbeaconsobject)
  * [onBeaconUpdate](iBeacon.md#onbeaconupdatecallback)
  * [onBeaconServiceChange](iBeacon.md#onbeaconservicechangecallback)