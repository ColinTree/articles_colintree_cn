# Activity启动器实用参数表

**本文档由ColinTree整理筛选自1.4.0版本APPINVActivityStarter（筛选规则：删减谷歌系列等国内无法使用的功能）**  
中文部分均为[ColinTree](mailto://502470184@qq.com)翻译。


*=Activity_with_text_data_result | Action | ActivityClass | ActivityPackage | DataType | DataUri | ExtraKey | ExtraValue
-|-|-|-|-|-|-|-
打开蓝牙 | android.bluetooth.adapter.action.REQUEST_ENABLE
使蓝牙可被检测 | android.bluetooth.adapter.action.REQUEST_DISCOVERABLE
安装应用 | android.intent.action.MAIN | com.android.packageinstaller.PackageInstallerActivity | com.android.packageinstaller |  | file:///mnt/sdcard/../XXX.apk
卸载应用 | android.intent.action.VIEW | com.android.packageinstaller.UninstallerActivity | com.android.packageinstaller |  | XXX
打开计算器 | android.intent.action.MAIN | com.android.calculator2.Calculator | com.android.calculator2
打开SIM卡应用 | android.intent.action.VIEW | com.android.stk.StkMenuActivity | com.android.stk
选择铃声 | android.intent.action.RINGTONE_PICKER
设置墙纸 | android.intent.action.SET_WALLPAPER
打开WiFi界面 | android.net.wifi.PICK_WIFI_NETWORK
查看下载 | android.intent.action.VIEW_DOWNLOADS
打开录相机 | android.media.action.VIDEO_CAMERA
打开相机 | android.media.action.STILL_IMAGE_CAMERA
调用拍照 * | android.media.action.IMAGE_CAPTURE
调用录像 * | android.media.action.VIDEO_CAPTURE
调用录音 * | android.media.action.RECORD_SOUND
设置新的锁屏密码 | android.app.action.SET_NEW_PASSWORD
音乐播放器 | android.intent.action.MUSIC_PLAYER
浏览器类型的应用的网络使用设置 | android.intent.action.MANAGE_NETWORK_USAGE
查看电池用量统计 | android.intent.action.POWER_USAGE_SUMMARY
拨号 | android.intent.action.CALL_BUTTON
最近通话记录 | com.android.phone.action.RECENT_CALLS
列出所有联系人 | com.android.contacts.action.LIST_ALL_CONTACTS
调用拨号 | android.intent.action.DIAL | | | | tel:号码
拨打号码 | android.intent.action.CALL | | | | tel:号码
视频拨号 | com.android.phone.videocall | | | | tel:号码
调用语音邮箱 | android.intent.action.DIAL | | | | voicemail:号码
写邮件 | android.intent.action.VIEW | | | | mailto:邮箱地址?subject=标题 | body | 内容
发短信 | android.intent.action.SENDTO | | | | smsto:号码 | sms_body | 信息内容
发彩信 | android.intent.action.SENDTO | | | | mmsto:号码 | mms_body | 信息内容
短信列表 | android.intent.action.MAIN | | | vnd.android-dir/mms-sms
打开日历 | android.intent.action.VIEW | | | vnd.android.cursor.item/event
添加日历活动 | android.intent.action.INSERT | | | vnd.android.cursor.item/event |  | title | 标题内容
选择联系人 * | android.intent.action.PICK | | | vnd.android.cursor.dir/person
打开网址 | android.intent.action.VIEW | | | | http://XXX
播放网络上的MP3文件 | android.intent.action.VIEW | com.android.internal.app.ResolverActivity | android | audio/mp3 | http://XXX/XXX.mp3
播放网络上的ASF文件 | android.intent.action.VIEW | com.android.internal.app.ResolverActivity | android | video/asf | http://XXX/XXX.asf
打开SD卡上的图片文件 | android.intent.action.VIEW | | | image/jpg | file:///mnt/sdcard/../XXX.jpg
打开SD卡上的视频文件 | android.intent.action.VIEW | | | video/mp4 | file:///mnt/sdcard/../XXX.mp4
分享文本 | android.intent.action.SEND | | | text/plain |  | android.intent.extra.TEXT | 文本内容
编辑SD卡上的txt文件 | android.intent.action.EDIT | | | text/plain | file:///mnt/sdcard/../XXX.txt
编辑SD卡上的jpg文件 | android.intent.action.EDIT | | | image/jpg | file:///mnt/sdcard/../XXX.jpg
把网址添加到书签栏 | android.intent.action.INSERT | | | vnd.android.cursor.dir/bookmark |  | url | http://XXX
打开本地网址 |  | com.android.htmlviewer.HTMLViewerActivity | com.android.htmlviewer |  | file:///mnt/sdcard/../XXX.html
设置图片 | android.intent.action.ATTACH_DATA | | | image/\* | file:///mnt/sdcard/../XXX.jpg
搜索 | android.intent.action.SEARCH | | | | | query | 内容
全局搜索 | android.intent.action.GLOBAL_SEARCH | | | | | query | 内容
网页搜索 | android.intent.action.WEB_SEARCH | | | | | query | 内容
网页语音搜索 | android.speech.action.WEB_SEARCH
搜索视频 | android.intent.action.MEDIA_SEARCH | | | | | query | 内容
播放搜索得到的视频 | android.intent.action.MEDIA_PLAY_FROM_SEARCH | | | | | query | 内容
语音搜索<br>（语音助手） | android.intent.action.SEARCH_LONG_PRESS
搜索已安装应用 | android.intent.action.SEARCH | com.android.providers.applications.ApplicationLauncher | com.android.providers.applications | | | query | 内容
选取文件 * | android.intent.action.GET_CONTENT | | | container/directory | file:///sdcard/
选取图片 * | android.intent.action.GET_CONTENT | | | image/\*
选取视频 * | android.intent.action.GET_CONTENT | | | video/\*
选择 * | android.intent.action.PICK | | | \*/\*
选择图片 * | android.intent.action.PICK | | | image/\*
选择视频 * | android.intent.action.PICK | | | video/\*
备份日历活动 | android.intent.action.MAIN | com.android.providers.calendar.CalendarDebugActivity | com.android.providers.calendar
Flash player<br>设置 | android.intent.action.MAIN | com.adobe.flashplayer.SettingsManager | com.adobe.flashplayer
ES文件浏览器<br>选择文件 * | com.estrongs.action.PICK_FILE
ES文件浏览器<br>选择文件夹 * | com.estrongs.action.PICK_DIRECTORY
ES文件浏览器<br>打开文件夹 | android.intent.action.VIEW | | | resource/folder | file:///sdcard/../

<br><br>

**以下是设置内容，不予翻译**

设置项目 | Action | ActivityClass
-|-|-
ACCESSIBILITY_SETTINGS | android.settings.ACCESSIBILITY_SETTINGS
ADD_ACCOUNT_SETTINGS | android.settings.ADD_ACCOUNT_SETTINGS
AIRLANE_MODE_SETTINGS | android.settings.AIRLANE_MODE_SETTINGS
APN_SETTINGS | android.settings.APN_SETTINGS
APPLICATION_DETAILS_SETTINGS | android.settings.APPLICATION_DETAILS_SETTINGS
APPLICATION_DEVELOPMENT_SETTINGS | android.settings.APPLICATION_DEVELOPMENT_SETTINGS
APPLICATION_SETTINGS | android.settings.APPLICATION_SETTINGS
BLUETOOTH_SETTINGS | android.settings.BLUETOOTH_SETTINGS
DATA_ROAMING_SETTINGS | android.settings.DATA_ROAMING_SETTINGS
DATE_SETTINGS | android.settings.DATE_SETTINGS
DEVICE_INFO_SETTINGS | android.settings.DEVICE_INFO_SETTINGS
DISPLAY_SETTINGS | android.settings.DISPLAY_SETTINGS
INPUT_METHOD_SETTINGS | android.settings.INPUT_METHOD_SETTINGS
INPUT_METHOD_SUBTYPE_SETTINGS | android.settings.INPUT_METHOD_SUBTYPE_SETTINGS
INTERNAL_STORAGE_SETTINGS | android.settings.INTERNAL_STORAGE_SETTINGS
LOCATION_SOURCE_SETTINGS | android.settings.LOCATION_SOURCE_SETTINGS
MANAGE_APPLICATIONS_SETTINGS | android.settings.MANAGE_APPLICATIONS_SETTINGS
MEMORY_APPLICATIONS_SETTINGS | android.settings.MEMORY_APPLICATIONS_SETTINGS
MEMORY_CARD_SETTINGS | android.settings.MEMORY_CARD_SETTINGS
NETWORK_OPERATOR_SETTINGS | android.settings.NETWORK_OPERATOR_SETTINGS
NFCSHARING_SETTINGS | android.settings.NFCSHARING_SETTINGS
NFC_SETTINGS | android.settings.NFC_SETTINGS
PRIVACY_SETTINGS | android.settings.PRIVACY_SETTINGS
QUICK_LAUNCH_SETTINGS | android.settings.QUICK_LAUNCH_SETTINGS
SEARCH_SETTINGS | android.settings.SEARCH_SETTINGS
SECURITY_SETTINGS | android.settings.SECURITY_SETTINGS
SETTINGS | android.settings.SETTINGS
SOUND_SETTINGS | android.settings.SOUND_SETTINGS
SYNC_SETTINGS | android.settings.SYNC_SETTINGS
USER_DICTIONARY_SETTINGS | android.settings.USER_DICTIONARY_SETTINGS
WIFI_SETTINGS | android.settings.WIFI_SETTINGS
WIRELESS_SETTINGS | android.settings.WIRELESS_SETTINGS
CallFeaturesSetting | com.android.phone.CallFeaturesSetting | com.android.phone
CdmaCallOptions | com.android.phone.CdmaCallOptions | com.android.phone
DataUsage | com.android.phone.DataUsage | com.android.phone
EmergencyDialer | com.android.phone.EmergencyDialer | com.android.phone
EnablelccPinScreen | com.android.phone.EnablelccPinScreen | com.android.phone
FdnList | com.android.phone.FdnList | com.android.phone
FdnSetting | com.android.phone.FdnSetting | com.android.phone
GsmUmtsAdditionalCallOptions | com.android.phone.GsmUmtsAdditionalCallOptions | com.android.phone
GsmUmtsCallForwardOptions | com.android.phone.GsmUmtsCallForwardOptions | com.android.phone
GsmUmtsCallOptions | com.android.phone.GsmUmtsCallOptions | com.android.phone
ManualSelectNetwork | com.android.phone.ManualSelectNetwork | com.android.phone
MobileNetworkSettings | com.android.phone.MobileNetworkSettings | com.android.phone
NetworkModeSelectionActivity | com.android.phone.NetworkModeSelectionActivity | com.android.phone
NetworkSetting | com.android.phone.NetworkSetting | com.android.phone
PhonePreference | com.android.phone.PhonePreference | com.android.phone
prefernetwork.OperatorSelectActivity | com.android.phone.prefernetwork.OperatorSelectActivity | com.android.phone
Settings | com.android.phone.Settings | com.android.phone
SimContact | com.android.phone.SimContact | com.android.phone
sip.SipSettings | com.android.phone.sip.SipSettings | com.android.phone
accounts.AddAccountSettings | com.android.settings.accounts.AddAccountSettings | com.android.settings
ApnSettings | com.android.settings.ApnSettings | com.android.settings
BandMode | com.android.settings.BandMode | com.android.settings
BatteryInfo | com.android.settings.BatteryInfo | com.android.settings
bluetooth.DevicePickerActivity | com.android.settings.bluetooth.DevicePickerActivity | com.android.settings
bluetoothAdvancedSettings | com.android.settings.bluetoothAdvancedSettings | com.android.settings
CdmaApnSettings | com.android.settings.CdmaApnSettings | com.android.settings
DateTimeSettingsSetupWizard | com.android.settings.DateTimeSettingsSetupWizard | com.android.settings
DevelopmentSettings | com.android.settings.DevelopmentSettings | com.android.settings
DeviceAdminSettings | com.android.settings.DeviceAdminSettings | com.android.settings
Display | com.android.settings.Display | com.android.settings
DisplaySettings | com.android.settings.DisplaySettings | com.android.settings
DockSettings | com.android.settings.DockSettings | com.android.settings
GSensorCalibration | com.android.settings.GSensorCalibration | com.android.settings
lccLockSettings | com.android.settings.lccLockSettings | com.android.settings
inputmethod.InputMethodAndSebtypeEnablerActivity | com.android.settings.inputmethod.InputMethodAndSebtypeEnablerActivity | com.android.settings
LanguageSettings | com.android.settings.LanguageSettings | com.android.settings
ManageApplications | com.android.settings.ManageApplications | com.android.settings
MediaFormat | com.android.settings.MediaFormat | com.android.settings
MediaFormatSD | com.android.settings.MediaFormatSD | com.android.settings
ProxySelector | com.android.settings.ProxySelector | com.android.settings
quicklaunch.QuickLaunchSettings | com.android.settings.quicklaunch.QuickLaunchSettings | com.android.settings
RadioInfo | com.android.settings.RadioInfo | com.android.settings
RunningServices | com.android.settings.RunningServices | com.android.settings
SecuritySettings | com.android.settings.SecuritySettings | com.android.settings
Settings | com.android.settings.Settings | com.android.settings
Settings$AccessibilitySettingsActivity | com.android.settings.Settings$AccessibilitySettingsActivity | com.android.settings
Settings$AdvancedWifiSettingsActivity | com.android.settings.Settings$AdvancedWifiSettingsActivity | com.android.settings
Settings$AndroidBeamSettingsActivity | com.android.settings.Settings$AndroidBeamSettingsActivity | com.android.settings
Settings$BluetoothSettingsActivity | com.android.settings.Settings$BluetoothSettingsActivity | com.android.settings
Settings$DataUsageSummaryActivity | com.android.settings.Settings$DataUsageSummaryActivity | com.android.settings
Settings$DataTimeSettingsActivity | com.android.settings.Settings$DataTimeSettingsActivity | com.android.settings
Settings$DeviceInfoSettingsActivity | com.android.settings.Settings$DeviceInfoSettingsActivity | com.android.settings
Settings$HDMI3DPlaySettingsActivity | com.android.settings.Settings$HDMI3DPlaySettingsActivity | com.android.settings
Settings$InputMethodAndLanguageSettingsActivity | com.android.settings.Settings$InputMethodAndLanguageSettingsActivity | com.android.settings
Settings$LocationSettingsActivity | com.android.settings.Settings$LocationSettingsActivity | com.android.settings
Settings$ManagerAccountsSettingsActivity | com.android.settings.Settings$ManagerAccountsSettingsActivity | com.android.settings
Settings$PowerUsageSummaryActivity | com.android.settings.Settings$PowerUsageSummaryActivity | com.android.settings
Settings$PrivacySettingsActivity | com.android.settings.Settings$PrivacySettingsActivity | com.android.settings
Settings$SpellCheckersSettingsActivity | com.android.settings.Settings$SpellCheckersSettingsActivity | com.android.settings
Settings$StorageUseActivity | com.android.settings.Settings$StorageUseActivity | com.android.settings
Settings$TextToSpeechSettingsActivity | com.android.settings.Settings$TextToSpeechSettingsActivity | com.android.settings
Settings$VpnSettingsActivity | com.android.settings.Settings$VpnSettingsActivity | com.android.settings
Settings$VpnSettingsActivity | com.android.settings.Settings$VpnSettingsActivity | com.android.settings
Settings$WifiP2pSettingsActivity | com.android.settings.Settings$WifiP2pSettingsActivity | com.android.settings
Settings$WirelessSettingsActivity | com.android.settings.Settings$WirelessSettingsActivity | com.android.settings
SettingsSafetyLegalActivity | com.android.settings.SettingsSafetyLegalActivity | com.android.settings
SoundSettings | com.android.settings.SoundSettings | com.android.settings
TestingSettings | com.android.settings.TestingSettings | com.android.settings
UsageStats | com.android.settings.UsageStats | com.android.settings
UsbSettings | com.android.settings.UsbSettings | com.android.settings
UserDictionarySettings | com.android.settings.UserDictionarySettings | com.android.settings
wifi.CWAcountInfo | com.android.settings.wifi.CWAcountInfo | com.android.settings
wifi.LanInfo | com.android.settings.wifi.LanInfo | com.android.settings
wifi.WifiAPITest | com.android.settings.wifi.WifiAPITest | com.android.settings
wifi.ConfigInfo | com.android.settings.wifi.ConfigInfo | com.android.settings
wifi.WifiInfo | com.android.settings.wifi.WifiInfo | com.android.settings
wifi.WifiSettings | com.android.settings.wifi.WifiSettings | com.android.settings
wifi.WifiStatusTest | com.android.settings.wifi.WifiStatusTest | com.android.settings
WifiApSettings | com.android.settings.WifiApSettings | com.android.settings