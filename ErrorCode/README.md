# AI运行错误代码对照


`错误原因`部分 和 `相关备注`部分，均由ColinTree一条条手动翻译，如有疏漏错误之处，敬请指出。  
使用搜索功能，在页面搜索错误码更加快速

**最后更新于2018.1.20**

{% raw %}
<style>
comp-name{font-size: smaller !important;}
</style>
{% endraw %}

错误码 | 错误原因 | 相关备注 | 错误发生范围 | 错误内容 | 英文原文
-|-|-|-|-|-
| **手机版本相关错误 - Phone version errors** |
1 | 拾取联系人邮件时发生错误 | *没有触发该错误码的情况* | 联系人选择框 / <comp-name>ContactPicker | ERROR_FUNCTIONALITY_NOT_SUPPORTED_CONTACT_EMAIL | Warning: This app contains functionality that does not work on this phone: picking an EmailAddress.</td>
2 | 无法使用邮箱选择器 | *没有触发该错误码的情况* | 邮箱地址选择框 / <comp-name>EmailPicker | ERROR_FUNCTIONALITY_NOT_SUPPORTED_EMAIL_PICKER | Warning: This app contains functionality that does not work on this phone: the EmailPicker component.</td>
3 | 不支持FushiontablesControl组件功能 |  | FusiontablesControl | ERROR_FUNCTIONALITY_NOT_SUPPORTED_FUSIONTABLES_CONTROL | Warning: This app contains functionality that does not work on this phone: the FusiontablesControl component.</td>
4 | Web组件不支持Cookie功能 |  | Web客户端 / <comp-name>Web | ERROR_FUNCTIONALITY_NOT_SUPPORTED_WEB_COOKIES | Warning: This app contains functionality that does not work on this phone: using cookies in the Web component.</td>
5 | 不支持WIFI点对点直连 | *没有触发该错误码的情况* | (没找到) | ERROR_FUNCTIONALITY_NOT_SUPPORTED_WIFI_DIRECT | Warning: This app contains functionality that does not work on this phone: Wi-Fi peer-to-peer connectivity.</td>
| **位置传感器相关错误 - LocationSensor errors** |
101 | 无法获取纬度信息 |  | 位置传感器 / <comp-name>LocationSensor | ERROR_LOCATION_SENSOR_LATITUDE_NOT_FOUND | Unable to find latitude from %s.</td>
102 | 无法获取经度信息 |  | 位置传感器 / <comp-name>LocationSensor | ERROR_LOCATION_SENSOR_LONGITUDE_NOT_FOUND | Unable to find longitude from %s.</td>
| **相机相关错误 - Camera errors** |
201 | 相机未返回图像 |  | 相机 / <comp-name>Camera | ERROR_CAMERA_NO_IMAGE_RETURNED | The camera did not return an image.</td>
| **推特客户端相关错误 - Twitter errors** |
301 | 不支持登录 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_UNSUPPORTED_LOGIN_FUNCTION | Twitter no longer supports this form of Login. Use the Authorize call instead.</td>
302 | 连接密钥错误 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_BLANK_CONSUMER_KEY_OR_SECRET | The ConsumerKey and ConsumerSecret properties must be set in order to authorize access for Twitter. Please obtain a Comsumer Key and Consumer Secret specific to your app from http:// twitter.com/oauth_clients/new</td>
303 | （就是个错误） | 由于国内也用不着，没深入研究 | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_EXCEPTION | Twitter error: %s</td>
304 | 无法获取安全验证标识 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_UNABLE_TO_GET_ACCESS_TOKEN | Unable to get access token: %s</td>
305 | 安全验证失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_AUTHORIZATION_FAILED | Twitter authorization failed</td>
306 | 获取状态信息失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_SET_STATUS_FAILED | SetStatus failed. %s</td>
307 | 请求谈论信息失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_REQUEST_MENTIONS_FAILED | RequestMentions failed. %s</td>
308 | 获取粉丝信息失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_REQUEST_FOLLOWERS_FAILED | RequestFollowers failed. %s</td>
309 | 获取最新私信失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_REQUEST_DIRECT_MESSAGES_FAILED | RequestDirectMessages failed. %s</td>
310 | 发送私信失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_DIRECT_MESSAGE_FAILED | DirectMessage failed. %s</td>
311 | 关注失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_FOLLOW_FAILED | Follow failed. %s</td>
312 | 停止关注失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_STOP_FOLLOWING_FAILED | StopFollowing failed. %s</td>
313 | 请求好友动态失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_REQUEST_FRIEND_TIMELINE_FAILED | Twitter RequestFriendTimeline failed: %s</td>
314 | 搜索失败 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_SEARCH_FAILED | Twitter search failed.</td>
315 | 图片路径错误 |  | 推特客户端 / <comp-name>Twitter | ERROR_TWITTER_INVALID_IMAGE_PATH | Invalid Path to Image; Update will not be sent.</td>
| **乐高相关错误 - LegoMindstormsNXT errors** |
401 | 蓝牙未连接 |  | 乐高 / <comp-name>NXT | ERROR_NXT_BLUETOOTH_NOT_SET | The Bluetooth property has not been set.</td>
402 | 机器未连接 |  | 乐高 / <comp-name>NXT | ERROR_NXT_NOT_CONNECTED_TO_ROBOT | Not connected to a robot.</td>
403 | 错误的返回数据包 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_RETURN_PACKAGE | Unable to receive return package. Has the robot gone to sleep?</td>
404 | 收到错误代码 |  | 乐高 / <comp-name>NXT | ERROR_NXT_ERROR_CODE_RECEIVED | Error code received from robot: %s.</td>
405 | 无效的应用名称 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_PROGRAM_NAME | Invalid program name.</td>
406 | 无效的文件名 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_FILE_NAME | Invalid file name.</td>
407 | 无效的电机端口 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_MOTOR_PORT | The NXT does not have a motor port labeled %s.</td>
408 | 无效的传感器端口 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_SENSOR_PORT | The NXT does not have a sensor port labeled %s.</td>
409 | 无效的邮箱 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_MAILBOX | The NXT does not have a mailbox number %s.</td>
410 | 消息太长 |  | 乐高 / <comp-name>NXT | ERROR_NXT_MESSAGE_TOO_LONG | The NXT only accepts messages up to 58 characters.</td>
411 | 数据太大 | 列表长度大于16会导致该错误 | NXT指令发送器 / <comp-name>NxtDirectCommands | ERROR_NXT_DATA_TOO_LARGE | The data is too large; it must be 16 bytes or less.</td>
412 | 无法解码列表项 | 看了一下，好像列表项不为数字就报错 | 乐高 / <comp-name>NXT | ERROR_NXT_COULD_NOT_DECODE_ELEMENT | Could not decode element %s as an integer.</td>
413 | 列表项无法解析 |  | 乐高 / <comp-name>NXT | ERROR_NXT_COULD_NOT_FIT_ELEMENT_IN_BYTE | Could not fit element %s into 1 byte.</td>
414 | 无效的源冲突 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_SOURCE_ARGUMENT | Invalid source argument.</td>
415 | 无效的目的文件 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_DESTINATION_ARGUMENT | Invalid destination argument.</td>
416 | 无法下载文件 |  | 乐高 / <comp-name>NXT | ERROR_NXT_UNABLE_TO_DOWNLOAD_FILE | Unable to download file to robot: %s</td>
417 | 无法检测颜色 |  | 乐高 / <comp-name>NXT | ERROR_NXT_CANNOT_DETECT_COLOR | Cannot detect color when the DetectColor property is set to False.</td>
418 | 无法检测光线 |  | 乐高 / <comp-name>NXT | ERROR_NXT_CANNOT_DETECT_LIGHT | Cannot detect light level when the DetectColor property is set to True.</td>
419 | 无效的生成颜色 |  | 乐高 / <comp-name>NXT | ERROR_NXT_INVALID_GENERATE_COLOR | "The GenerateColor property is limited to None, Red, Green, or Blue."</td>
| **蓝牙相关错误 - Bluetooth errors** |
501 | 蓝牙不可用 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_NOT_AVAILABLE | Bluetooth is not available.</td>
502 | 蓝牙未开启 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_NOT_ENABLED | Bluetooth is not available.</td>
503 | 无效的地址 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_INVALID_ADDRESS | The specified address is not a valid Bluetooth MAC address.</td>
504 | 连接的设备还未配对 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_NOT_PAIRED_DEVICE | The specified address is not a paired Bluetooth device.</td>
505 | 不是正确的设备类型（不支持） | 这个不是很肯定 | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_NOT_REQUIRED_CLASS_OF_DEVICE | The specified address is not the required class of device.</td>
506 | 无效的UUID |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_INVALID_UUID | "The UUID \""%s\"" is not formatted correctly."</td>
507 | 无法连接 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNABLE_TO_CONNECT | Unable to connect. Is the device turned on?</td>
508 | 无法监听 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNABLE_TO_LISTEN | Unable to listen for a connection from a bluetooth device.</td>
509 | 无法允许 | 这个不是很肯定 | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNABLE_TO_ACCEPT | Unable to accept a connection from a bluetooth device.</td>
510 | 无法解码 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_COULD_NOT_DECODE | "Could not decode \""%s\"" as an integer."</td>
511 | 无法转换为字节(BYTE) |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_COULD_NOT_FIT_NUMBER_IN_BYTE | "Could not fit \""%s\"" into 1 byte."</td>
512 | 无法转换为字节(BYTES) |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_COULD_NOT_FIT_NUMBER_IN_BYTES | "Could not fit \""%s\"" into %s bytes."</td>
513 | 无法解码列表元素 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_COULD_NOT_DECODE_ELEMENT | Could not decode element %s as an integer.</td>
514 | 无法将元素装换为字节(BYTE) |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_COULD_NOT_FIT_ELEMENT_IN_BYTE | Could not fit element %s into 1 byte.</td>
515 | 无法连接至设备 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_NOT_CONNECTED_TO_DEVICE | Not connected to a Bluetooth device.</td>
516 | 无法进行写操作 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNABLE_TO_WRITE | Unable to write: %s</td>
517 | 无法进行读操作 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNABLE_TO_READ | Unable to read: %s</td>
518 | 遇到数据流结尾 | 这个不是很肯定 | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_END_OF_STREAM | End of stream has been reached.</td>
519 | 不支持的编码类型 |  | 蓝牙 / <comp-name>Bluetooth | ERROR_BLUETOOTH_UNSUPPORTED_ENCODING | The encoding %s is not supported.</td>
| **Activity启动器相关错误 - ActivityStarter errors** |
601 | 没有找到相应的Activity |  | Activity启动器 / <comp-name>ActivityStarter | ERROR_ACTIVITY_STARTER_NO_CORRESPONDING_ACTIVITY | No corresponding activity was found.</td>
602 | 没有找到ActivityStarter中的操作信息 |  | Activity启动器 / <comp-name>ActivityStarter | ERROR_ACTIVITY_STARTER_NO_ACTION_INFO | No Action information in ActivityStarter was found.</td>
| **媒体相关错误 - Media errors** |
701 | 无法加载媒体文件 |  |  | ERROR_UNABLE_TO_LOAD_MEDIA | Unable to load %s.</td>
702 | 无法准备媒体文件 | 应该是指的预处理 |  | ERROR_UNABLE_TO_PREPARE_MEDIA | Unable to prepare %s.</td>
703 | 无法播放媒体文件 |  |  | ERROR_UNABLE_TO_PLAY_MEDIA | Unable to play %s.</td>
704 | 外部储存(SD卡)是只读状态 | 有时未开启写权限会导致该问题 |  | ERROR_MEDIA_EXTERNAL_STORAGE_READONLY | External storage is available but read-only.</td>
705 | 外部储存不可用 |  |  | ERROR_MEDIA_EXTERNAL_STORAGE_NOT_AVAILABLE | External storage is not available.</td>
706 | 媒体文件格式错误 | 原文中指出必须是jpg图片或者png图片 |  | ERROR_MEDIA_IMAGE_FILE_FORMAT | "Image file name must end in \"".jpg\"", \"".jpeg\"", or \"".png\""."</td>
707 | 无法打开文件 |  |  | ERROR_MEDIA_CANNOT_OPEN | Cannot open file %s.</td>
708 | 获取文件的时候发生错误：…… | 省略号内容由程序自动添加 |  | ERROR_MEDIA_FILE_ERROR | Got file error: %s.</td>
709 | 音频输出流无法授予给…… | 省略号内容由程序自动添加 |  | ERROR_UNABLE_TO_FOCUS_MEDIA | Unable to grant exclusive lock of audio output stream to %s.</td>
710 | 音频文件还未准备完成 |  |  | ERROR_SOUND_NOT_READY | The sound is not ready to play: %s.</td>
711 | 也就是需要等待程序加载文件 | *没有触发该错误码的情况* |  | ERROR_OUT_OF_MEMORY_LOADING_MEDIA | Not Enough Memory to load: %s.</td>
712 | 播放器音量错误 |  | 播放器 / <comp-name>Player | ERROR_PLAYER_INVALID_VOLUME | Invalid volume: %s. Volume must be set to a number between 0 and 100.
| **录音器相关错误 - SoundRecorder errors** |
801 | 未知的错误 |  | 录音器 / <comp-name>SoundRecorder | ERROR_SOUND_RECORDER | An unexpected error occurred while recording sound.</td>
802 | 无法录制 |  | 录音器 / <comp-name>SoundRecorder | ERROR_SOUND_RECORDER_CANNOT_CREATE | Cannot start recording: %s</td>
803 | 在没有录音的情况下调用停止 |  | 录音器 / <comp-name>SoundRecorder | ERROR_SOUND_RECORDER_ILLEGAL_STOP | Stop() called when not recording.
804 | 达到最大录音事件长度 |  | 录音器 / <comp-name>SoundRecorder | ERROR_SOUND_RECORDER_MAX_DURATION_REACHED | Maximum sound recording duration was reached.
805 | 达到最大录音文件大小 |  | 录音器 / <comp-name>SoundRecorder | ERROR_SOUND_RECORDER_MAX_FILESIZE_REACHED | Maximum sound recording size was reached.
| **屏幕相关错误 - Form errors** |
901 | 屏幕方向参数错误 |  | 屏幕相关 | ERROR_INVALID_SCREEN_ORIENTATION | The specified screen orientation is not valid: %s</td>
902 | 未找到屏幕xxx | 出现于打开新屏幕时，请检查拼写，包括大小写 | 屏幕相关 | ERROR_SCREEN_NOT_FOUND | Screen not found: %s</td>
903 | 从另一个屏幕收到“坏值” | “坏值”即无法被处理的值 | 屏幕相关 | ERROR_SCREEN_BAD_VALUE_RECEIVED | Bad value received from other screen: %s</td>
904 | 发送到另一个屏幕失败：出现“坏值” | “坏值”即无法被处理的值 | 屏幕相关 | ERROR_SCREEN_BAD_VALUE_FOR_SENDING | Bad value for sending to other screen: %s</td>
905 | 屏幕动画参数错误 |  | 屏幕相关 | ERROR_SCREEN_INVALID_ANIMATION | Bad value for screen open/close animation: %s</td>
906 | 未找到可以聚焦的可视组件 | *没有触发该错误码的情况* | 屏幕相关 | ERROR_NO_FOCUSABLE_VIEW_FOUND | No Focusable View Found</td>
907 | 手机不支持ActionBar |  | 屏幕相关 | ERROR_ACTIONBAR_NOT_SUPPORTED | ActionBar is not supported on this device.
| **画布相关错误 - Canvas errors** |
1001 | 画布内部错误 |  | 画布 / <comp-name>Canvas | ERROR_CANVAS_BITMAP_ERROR | Error getting Canvas contents to save</td>
1002 | 画布宽度需要是正数 |  | 画布 / <comp-name>Canvas | ERROR_CANVAS_WIDTH_ERROR | Canvas width cannot be set to non-positive number</td>
1003 | 画布高度需要是正数 |  | 画布 / <comp-name>Canvas | ERROR_CANVAS_HEIGHT_ERROR | Canvas height cannot be set to non-positive number</td>
| **Web客户端相关错误 - Web errors** |
1101 | 无法执行GET请求 |  | Web客户端 / <comp-name>Web | ERROR_WEB_UNABLE_TO_GET | Unable to get a response with the specified URL: %s</td>
1102 | 不支持的编码格式 |  | Web客户端 / <comp-name>Web | ERROR_WEB_UNSUPPORTED_ENCODING | The encoding %s is not supported.</td>
1103 | 无法POST或PUT |  | Web客户端 / <comp-name>Web | ERROR_WEB_UNABLE_TO_POST_OR_PUT | "Unable to post or put the text \""%s\"" with the specified URL: %s"</td>
1104 | 无法POST或PUT文件 |  | Web客户端 / <comp-name>Web | ERROR_WEB_UNABLE_TO_POST_OR_PUT_FILE | "Unable to post or put the file \""%s\"" with the specified URL %s."</td>
1105 | 无法解码JSON |  | Web客户端 / <comp-name>Web | ERROR_WEB_JSON_TEXT_DECODE_FAILED | Unable to decode the JSON text: %s</td>
1106 | 无法解码HTML编码 |  | Web客户端 / <comp-name>Web | ERROR_WEB_HTML_TEXT_DECODE_FAILED | Unable to decode the HTML text: %s</td>
1107-1108被下面占用了 |
1109 | 无效的网址(URL) |  | Web客户端 / <comp-name>Web | ERROR_WEB_MALFORMED_URL | The specified URL is not valid: %s</td>
1110 | 错误：请求头不是列表 |  | Web客户端 / <comp-name>Web | ERROR_WEB_REQUEST_HEADER_NOT_LIST | The specified request headers are not valid: element %s is not a list</td>
1111 | 错误：请求头格式错误 | 请求头列表必须为键值对格式 | Web客户端 / <comp-name>Web | ERROR_WEB_REQUEST_HEADER_NOT_TWO_ELEMENTS | The specified request headers are not valid: element %s does not contain two elements</td>
1112 | 错误：请求数据不是列表 |  | Web客户端 / <comp-name>Web | ERROR_WEB_BUILD_REQUEST_DATA_NOT_LIST | Unable to build request data: element %s is not a list</td>
1113 | 错误：请求数据列表格式错误 | 同样需要是键值对 | Web客户端 / <comp-name>Web | ERROR_WEB_BUILD_REQUEST_DATA_NOT_TWO_ELEMENTS | Unable to build request data: element %s does not contain two elements</td>
1114 | 错误：无法发送DELETE请求 |  | Web客户端 / <comp-name>Web | ERROR_WEB_UNABLE_TO_DELETE | Unable to delete a resource with the specified URL: %s</td>
1115 | 无法解码XML |  | Web客户端 / <comp-name>Web | ERROR_WEB_XML_TEXT_DECODE_FAILED | Unable to decode the XML text: %s</td>
| **联系人选择框相关错误 - Contact picker (and PhoneNumberPicker) errors** |
1107 | 手机不支持联系人选择 |  | 联系人选择框 / <comp-name>ContactPicker | ERROR_PHONE_UNSUPPORTED_CONTACT_PICKER | The software used in this app cannot extract contacts from this type of phone.</td>
1108 | 手机不支持联系人选择中的搜索 |  | 联系人选择框 / <comp-name>ContactPicker | ERROR_PHONE_UNSUPPORTED_SEARCH_IN_CONTACT_PICKING | "To pick contacts, pick them directly, without using search."</td>
| **摄像机相关错误 - Camcorder errors** |
1201 | 镜头未返回画面 |  | 摄像机 / <comp-name>Camcorder | ERROR_CAMCORDER_NO_CLIP_RETURNED | The camcorder did not return a clip.</td>
| **视频播放器相关错误 - VideoPlayer errors** |
1301 | 无法打开全屏 |  | 视频播放器 / <comp-name>VideoPlayer | ERROR_VIDEOPLAYER_FULLSCREEN_UNAVAILBLE | Cannot start fullscreen mode.</td>
1302 | 全屏无法退出 |  | 视频播放器 / <comp-name>VideoPlayer | ERROR_VIDEOPLAYER_FULLSCREEN_CANT_EXIT | Cannot exit fullscreen mode.</td>
1303 | 不支持全屏 |  | 视频播放器 / <comp-name>VideoPlayer | ERROR_VIDEOPLAYER_FULLSCREEN_UNSUPPORTED | Fullscreen mode not supported on this version of Android.</td>
| **布局相关错误 - Arrangement errors** |
1401 | 布局水平对齐参数错误 | 必须是1/2/3 | 适用布局组件 | ERROR_BAD_VALUE_FOR_HORIZONTAL_ALIGNMENT | "The value -- %s -- provided for HorizontalAlignment was bad.  The only legal values are 1, 2, or 3."</td>
1402 | 布局垂直对齐参数错误 | 必须是1/2/3 | 适用布局组件 | ERROR_BAD_VALUE_FOR_VERTICAL_ALIGNMENT | "The value -- %s -- provided for VerticalAlignment was bad.  The only legal values are 1, 2, or 3."</td>
| **条码扫描器相关错误 - BarcodeScanner errors** |
1501 | 未找到合适的扫码器 |  | 条码扫描器 / <comp-name>BarcodeScanner | ERROR_NO_SCANNER_FOUND | Your device does not have a scanning application installed.</td>
| **图片选择框相关错误 - ImagePicker errors** |
1601 | 无法保存照片 |  | 图像选择框 / <comp-name>ImagePicker | ERROR_CANNOT_SAVE_IMAGE | Unable to save image: %s</td>
1602 | 无法复制 |  | 图像选择框 / <comp-name>ImagePicker | ERROR_CANNOT_COPY_MEDIA | Unable to copy selected media: %s</td>
| **信息收发器相关错误 - Texting errors** |
1701 | 错误的“启用消息接收”属性 |  | 短信收发器 / <comp-name>Texting | ERROR_BAD_VALUE_FOR_TEXT_RECEIVING | "Text Receiving should be either 1, 2 or 3."</td>
| **AI伴侣相关错误 - Repl Communication Errors** |
1801 | REPL安全错误 | 接受不安全的代码块信息 | AI伴侣 | ERROR_REPL_SECURITY_ERROR | Security Error Receiving Blocks from Browser.</td>
| **方向传感器相关错误 - AccelerometerSensor Errors** |
1901 | 错误的“敏感度”属性 | 必须为1或2或3 | 方向传感器 / <comp-name>AccelerometerSensor | ERROR_BAD_VALUE_FOR_ACCELEROMETER_SENSITIVITY | "The value -- %s -- provided for AccelerometerSensor's sensitivity was bad. The only legal values are 1, 2, or 3."</td>
| **信息分享器相关错误 - Sharing Errors** |
2001 | 无法找到要分享的文件 |  | 信息分享器 / <comp-name>Sharing | ERROR_FILE_NOT_FOUND_FOR_SHARING | The File %s could not be found on your device.</td>
| **文件管理器相关错误 - File errors** |
2101 | 未找到文件 |  | 文件管理器 / <comp-name>File | ERROR_CANNOT_FIND_FILE | The file %s could not be found</td>
2102 | 无法读取文件 |  | 文件管理器 / <comp-name>File | ERROR_CANNOT_READ_FILE | The file %s could not be opened</td>
2103 | 无法创建文件 |  | 文件管理器 / <comp-name>File | ERROR_CANNOT_CREATE_FILE | The file %s could not be created</td>
2104 | 无法写入文件 |  | 文件管理器 / <comp-name>File | ERROR_CANNOT_WRITE_TO_FILE | Cannot write to file %s</td>
2105 | 无法删除ASSET | ASSET:应用自带数据，即上传至AI的文件 | 文件管理器 / <comp-name>File | ERROR_CANNOT_DELETE_ASSET | Cannot delete asset file at %s</td>
2106 | 无法写入ASSET | ASSET:应用自带数据，即上传至AI的文件 | 文件管理器 / <comp-name>File | ERROR_CANNOT_WRITE_ASSET | Cannot write asset file at %s</td>
| **Yandex翻译相关错误 - Yandex.Translate errors** |
2201 | 未找到翻译功能连接秘钥 |  | YandexTranslate / <comp-name>Yandex语言翻译器 | ERROR_TRANSLATE_NO_KEY_FOUND | Missing API key for the Yandex.Translate service.</td>
2202 | 服务不可用 |  | YandexTranslate / <comp-name>Yandex语言翻译器 | ERROR_TRANSLATE_SERVICE_NOT_AVAILABLE | The translation service is not available; Please try again later.</td>
2203 | 解析JSON结果错误 |  | YandexTranslate / <comp-name>Yandex语言翻译器 | ERROR_TRANSLATE_JSON_RESPONSE | The response from the Yandex.Translate service cannot be parsed; Please try again later.</td>
| **时间选择框相关错误 - TimePicker errors** |
2301 | 不合规的小时数 |  | 时间选择框 / <comp-name>TimePicker | ERROR_ILLEGAL_HOUR | The hour must be set to a value between 0 and 23.</td>
2302 | 不合规的分钟数 |  | 时间选择框 / <comp-name>TimePicker | ERROR_ILLEGAL_MINUTE | The minute must be set to a value between 0 and 59.</td>
| **时期选择框相关错误 - DatePicker errors** |
2401 | 不合规的日期 |  | 日期选择框 / <comp-name>DatePicker | ERROR_ILLEGAL_DATE | The date you entered is invalid.</td>
| **Web浏览框 - WebViewer errors** |
2501 | 网页SSL错误 | SSL:安全套接层，网页安全传输协议的一种 | Web浏览框 / <comp-name>WebViewer | ERROR_WEBVIEW_SSL_ERROR | SSL Connection could not complete.</td>
| **FusiontablesControl errors** |
2601 | Fusion table 查询错误 |  | FusiontablesControl | FUSION_TABLES_QUERY_ERROR | Fusion tables returned an error. The query was: %s. The response was: %s</td>
| **TTS相关错误 - TextToSpeech errors** |
2701 | TTS尚未准备完成 |  | 文本语音转换器 / <comp-name>TextToSpeech | ERROR_TTS_NOT_READY | TextToSpeech is not yet ready to perform this operation</td>
| **可视组件相关错误 - AndroidViewComponent errors** |
2801 | 百分比范围错误 |  | (适用所有可视组件) | ERROR_BAD_PERCENT | Percent values should be between 0 and 100.</td>
| **2901-2999留给第一届的某科技竞赛了** | **2901-2999 are reserved for FIRST Tech Challenge.** |
| **图像相关错误 - Image errors** |
3001 | 图像无法选装 |  | 图像/Image | ERROR_IMAGE_CANNOT_ROTATE | The version of Android on this device does not support image rotation.</td>
| **乐高EV3相关错误 - LegoMindstormsEv3 errors** |
3100 | 蓝牙未连接 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_BLUETOOTH_NOT_SET | The Bluetooth property has not been set.</td>
3101 | 机器未连接 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_NOT_CONNECTED_TO_ROBOT | Cannot connect to an EV3 robot. Has the robot gone to sleep?</td>
3102 | 错误的返回信息 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_INVALID_REPLY | Unable to receive a reply or the reply cannot be understood.</td>
3103 | 无效的内容冲突 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_ILLEGAL_ARGUMENT | Illegal argument: %s</td>
3104 | 无效的电机端口 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_ILLEGAL_MOTOR_PORT | Cannot understant motor port: %s</td>
3105 | 无效的传感器端口 |  | 乐高Ev3 / <comp-name>EV3 | ERROR_EV3_ILLEGAL_SENSOR_PORT | Cannot understant sensor port: %s</td>
| **其它错误 - Form errors signaled in runtime.scm.** |
3200 | 遇到除以零的情况 |  | 计算中出现的错误 | ERROR_DIVISION_BY_ZERO | Trying to divide %s by 0.  The result might not be valid.</td>
| **Extension errors are signalled from extensions** |
3300 | 拓展报的错误 |  | 拓展组件 | ERROR_EXTENSION_ERROR | Error %d in extension %s: %s
| **Map组件相关错误 - Map errors** |
3401 | 绘制直线需要两个点 |  | LineString | ERROR_LINESTRING_TOO_FEW_POINTS | Need at least 2 points for a LineString. Got only %1$d.
3402 | 解析直线发生错误 |  | LineString | ERROR_LINESTRING_PARSE_ERROR | Parse error attempting to create LineString: %1$s.
3403 | 点的参数太少 |  | LineString | ERROR_LINESTRING_TOO_FEW_FIELDS | Too few fields in point. Expected 2, got %2$d.
3404 | 解析多边形发生错误 |  | Polygon | ERROR_POLYGON_PARSE_ERROR | Parse error attempting to create Polygon: %1$s.
3405 | 点的参数不对 |  | Rectangle | ERROR_INVALID_POINT | Invalid value for point (%1$s, %2$s).
3406 | 某位置的点参数不对 |  |  | ERROR_INVALID_POINT_AT_INDEX | Invalid value for point at index %1$d (%2$s, %3$s).
3407 | 某位置的类型不对 |  |  | ERROR_INVALID_TYPE_AT_INDEX | Invalid type %2$s at index %1$d. Expected %3$s.
3408 | 某位置的值数量不对 |  |  | ERROR_INVALID_NUMBER_OF_VALUES_IN_POINT_AT_INDEX | Invalid number of values in point at index %1$d. Expected %2$d but found %3$d.
3409 | 点的值数量不对 |  |  | ERROR_INVALID_NUMBER_OF_VALUES_IN_POINT | Invalid number of values in point. Expected %1$d but found %2$d.
3410 | 类型不对 |  |  | ERROR_INVALID_TYPE | Invalid type %1$s. Expected %2$s.
3411 | GeoJson解析不了 |  |  | ERROR_INVALID_GEOJSON | Unable to parse GeoJSON content for the reason: %1$s.
3412 | 保存地图期间发生错误 |  | Map | ERROR_EXCEPTION_DURING_MAP_SAVE | Unable to save Map due to an internal exception: %1$s.
3413 | 纬度不在-90到90之间 |  | Circle, Marker | ERROR_INVALID_LATITUDE | Latitude %1$f was not in the expected range [-90, 90].
3414 | 经度不在-180到180之间 |  | Circle, Marker | ERROR_INVALID_LONGITUDE | Longitude %1$f was not in the expected range [-180, 180].
3415 | 无法创建tile缓存 | *没有触发该错误码的情况* | Map | ERROR_UNABLE_TO_CREATE_TILE_CACHE | Unable to create a tile cache for maps.
3416 | Marker竖直位置不对 |  | Marker | ERROR_INVALID_ANCHOR_VERTICAL | Invalid value %1$d given for AnchorVertical. Valid settings are 1, 2, or 3.
3417 | Marker横向位置不对 |  | Marker | ERROR_INVALID_ANCHOR_HORIZONTAL | Invalid value %1$d given for AnchorHorizontal. Valid settings are 1, 2, or 3.
3418 | 某位置的点的纬度不对 |  | LineString | ERROR_INVALID_LATITUDE_IN_POINT_AT_INDEX | Invalid latitude %2$s in point at index %1$d. Expected a value between [-90, 90].
3419 | 某位置的点的经度不对 |  | LineString | ERROR_INVALID_LONGITUDE_IN_POINT_AT_INDEX | Invalid longitude %2$s in point at index %1$d. Expected a value between [-180, 180].
3420 | 某位置的值不是一个列表 |  | LineString | ERROR_EXPECTED_ARRAY_AT_INDEX | Expected an array of values at index %1$d, but got %2$s.