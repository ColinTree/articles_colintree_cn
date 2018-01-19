# Activity启动器实用参数表-未翻译完整版

**本文档由ColinTree整理自1.4.0版本APPINVActivityStarter**

Class | *=Activity_with_text_data_result | Action | ActivityClass | ActivityPackage | DataType | DataUri | ExtraKey | ExtraValue
-|-|-|-|-|-|-|-|-
Miscellaneous | Enable Bluetooth | android.bluetooth.adapter.action.REQUEST_ENABLE
. | Bluetooth Discoverable | android.bluetooth.adapter.action.REQUEST_DISCOVERABLE
. | Install Application | android.intent.action.MAIN | com.android.packageinstaller.PackageInstallerActivity | com.android.packageinstaller |  | file:///mnt/sdcard/../XXX.apk
. | Uninstall Application | android.intent.action.VIEW | com.android.packageinstaller.UninstallerActivity | com.android.packageinstaller |  | XXX
. | Open Calculator | android.intent.action.MAIN | com.android.calculator2.Calculator | com.android.calculator2
. | Sim Toolkit Application (STK) | android.intent.action.VIEW | com.android.stk.StkMenuActivity | com.android.stk
. | RINGTONE_PICKER | android.intent.action.RINGTONE_PICKER
. | SET_WALLPAPER | android.intent.action.SET_WALLPAPER
. | PICK_WIFI_NETWORK | android.net.wifi.PICK_WIFI_NETWORK
. | VIEW_DOWNLOADS | android.intent.action.VIEW_DOWNLOADS
. | VIDEO_CAMERA | android.media.action.VIDEO_CAMERA
. | STILL_IMAGE_CAMERA | android.media.action.STILL_IMAGE_CAMERA
. | IMAGE_CAPTURE * | android.media.action.IMAGE_CAPTURE
. | VIDEO_CAPTURE * | android.media.action.VIDEO_CAPTURE
. | RECORD_CAPTURE * | android.media.action.RECORD_SOUND
. | SET_NEW_PASSWORD | android.app.action.SET_NEW_PASSWORD
. | MUSIC_PLAYER | android.intent.action.MUSIC_PLAYER
. | MANAGE_NETWORK_USAGE | android.intent.action.MANAGE_NETWORK_USAGE
. | POWER_USAGE_SUMMARY | android.intent.action.POWER_USAGE_SUMMARY
Social: Call, email, sms, contacts | CALL_BUTTON | android.intent.action.CALL_BUTTON
. | RECENT_CALLS | com.android.phone.action.RECENT_CALLS
. | LIST_ALL_CONTACTS | com.android.contacts.action.LIST_ALL_CONTACTS
. | LIST_DEFAULT | com.android.contacts.action.LIST_DEFAULT
. | LIST_CONTACTS_WITH_PHONES | com.android.contacts.action.LIST_CONTACTS_WITH_PHONES
. | LIST_FREQUENT | com.android.contacts.action.LIST_FREQUENT
. | LIST_STREQUENT | com.android.contacts.action.LIST_STREQUENT
. | LIST_STARRED | com.android.contacts.action.LIST_STARRED
. | Dail number | android.intent.action.DIAL | | | | tel:号码
. | Call number | android.intent.action.CALL | | | | tel:号码
. | Video call number | com.android.phone.videocall | | | | tel:号码
. | Dial voicemail | android.intent.action.DIAL | | | | voicemail:号码
. | Call contact phone id | android.intent.action.CALL | | | vnd.android.cursor.item/phone | content://com.android.contacts/data/1139
. | Email to | android.intent.action.VIEW | | | | mailto:邮箱地址?subject=标题 | body | 内容
. | SMS to nr | android.intent.action.SENDTO | | | | smsto:号码 | sms_body | 信息内容
. | MMS to nr | android.intent.action.SENDTO | | | | mmsto:号码 | mms_body | 信息内容
. | Open sms mms in box | android.intent.action.MAIN | | | vnd.android-dir/mms-sms
. | Open Calendar app | android.intent.action.VIEW | | | vnd.android.cursor.item/event
. | Insert calendar event | android.intent.action.INSERT | | | vnd.android.cursor.item/event |  | title | 标题内容
. | Open contact nr XXX | android.intent.action.VIEW | | | | content://contacts/people/XXX | | | Change the DataUri to an ID form your address book.Use "Pick contact"
. | Edit contact nr XXX | android.intent.action.EDIT | | | | content://contacts/people/XXX | | | Change the DataUri to an ID form your address book.Use "Pick contact"
. | PICK contact * | android.intent.action.PICK | | | vnd.android.cursor.dir/person
. | Get id contact * | android.intent.action.GET_CONTENT | | | vnd.android.cursor.item/contact
. | Get id contact person * | android.intent.action.GET_CONTENT | | | vnd.android.cursor.item/person
. | Get id contact phone * | android.intent.action.GET_CONTENT | | | vnd.android.cursor.item/phone
. | Get id contact address * | android.intent.action.GET_CONTENT | | | vnd.android.cursor.item/postal-address
Content:Open,pick,search,edit | Opening a url | android.intent.action.VIEW | | | | http://XXX
. | Play a mp3 stream | android.intent.action.VIEW | com.android.internal.app.ResolverActivity | android | audio/mp3 | http://XXX/XXX.mp3
. | Play a asf stream | android.intent.action.VIEW | com.android.internal.app.ResolverActivity | android | video/asf | http://XXX/XXX.asf
. | View image on SD | android.intent.action.VIEW | | | image/jpg | file:///mnt/sdcard/../XXX.jpg
. | View video on SD | android.intent.action.VIEW | | | video/mp4 | file:///mnt/sdcard/../XXX.mp4
. | Share text | android.intent.action.SEND | | | text/plain |  | android.intent.extra.TEXT | 文本内容
. | Edit text on SD | android.intent.action.EDIT | | | text/plain | file:///mnt/sdcard/../XXX.txt
. | Edit jpg on SD | android.intent.action.EDIT | | | image/jpg | file:///mnt/sdcard/../XXX.jpg
. | INSERT browser bookmark | android.intent.action.INSERT | | | vnd.android.cursor.dir/bookmark |  | url | http://XXX
. | Html Viewer local file |  | com.android.htmlviewer.HTMLViewerActivity | com.android.htmlviewer |  | file:///mnt/sdcard/../XXX.html
. | Image ATTACH_DATA | android.intent.action.ATTACH_DATA | | | image/\* | file:///mnt/sdcard/../XXX.jpg
. | SEARCH | android.intent.action.SEARCH | | | | | query | 内容
. | GLOBAL_SEARCH | android.intent.action.GLOBAL_SEARCH | | | | | query | 内容
. | WEB_SEARCH | android.intent.action.WEB_SEARCH | | | | | query | 内容
. | Speech WEB_SEARCH | android.speech.action.WEB_SEARCH
. | MEDIA_SEARCH | android.intent.action.MEDIA_SEARCH | | | | | query | 内容
. | MEDIA_PLAY_FROM_SEARCH | android.intent.action.MEDIA_PLAY_FROM_SEARCH | | | | | query | 内容
. | SEARCH_LONG_PRESS | android.intent.action.SEARCH_LONG_PRESS
. | Search installed apps | android.intent.action.SEARCH | com.android.providers.applications.ApplicationLauncher | com.android.providers.applications | | | query | 内容
. | GET_CONTENT * | android.intent.action.GET_CONTENT
. | GET a file * | android.intent.action.GET_CONTENT | | | container/directory | file:///sdcard/
. | GET a image * | android.intent.action.GET_CONTENT | | | image/\*
. | GET a video * | android.intent.action.GET_CONTENT | | | video/\*
. | PICK * | android.intent.action.PICK | | | \*/\*
. | Pick image * | android.intent.action.PICK | | | image/\*
. | Pick video * | android.intent.action.PICK | | | video/\*
. | Backup calendar database | android.intent.action.MAIN | com.android.providers.calendar.CalendarDebugActivity | com.android.providers.calendar
Location: Geo, maps | Show map for contact postal-address id | android.intent.action.VIEW | | | vnd.android.cursor.item/postal-address | content://com.android.contacts/data/396	
. | Show map for location | android.intent.action.VIEW | | | | geo:52.377348,4.745877
External apps | Chrome - add Bookmark url | android.intent.action.VIEW | com.google.android.apps.chrome.ManageBookmarkActivity | com.android.chrome | text/plain | | url | http://XXX
. | Flash player - settings and Check installed | android.intent.action.MAIN | com.adobe.flashplayer.SettingsManager | com.adobe.flashplayer
. | ES File Explorer - Pick a file * | com.estrongs.action.PICK_FILE
. | ES File Explorer - Pick a directory * | com.estrongs.action.PICK_DIRECTORY
. | ES File Explorer - Open a directory | android.intent.action.VIEW | | | resource/folder | file:///sdcard/../
android.settings activity actions | ACCESSIBILITY_SETTINGS | android.settings.ACCESSIBILITY_SETTINGS
. | ADD_ACCOUNT_SETTINGS | android.settings.ADD_ACCOUNT_SETTINGS
. | AIRLANE_MODE_SETTINGS | android.settings.AIRLANE_MODE_SETTINGS
. | APN_SETTINGS | android.settings.APN_SETTINGS
. | APPLICATION_DETAILS_SETTINGS | android.settings.APPLICATION_DETAILS_SETTINGS
. | APPLICATION_DEVELOPMENT_SETTINGS | android.settings.APPLICATION_DEVELOPMENT_SETTINGS
. | APPLICATION_SETTINGS | android.settings.APPLICATION_SETTINGS
. | BLUETOOTH_SETTINGS | android.settings.BLUETOOTH_SETTINGS
. | DATA_ROAMING_SETTINGS | android.settings.DATA_ROAMING_SETTINGS
. | DATE_SETTINGS | android.settings.DATE_SETTINGS
. | DEVICE_INFO_SETTINGS | android.settings.DEVICE_INFO_SETTINGS
. | DISPLAY_SETTINGS | android.settings.DISPLAY_SETTINGS
. | INPUT_METHOD_SETTINGS | android.settings.INPUT_METHOD_SETTINGS
. | INPUT_METHOD_SUBTYPE_SETTINGS | android.settings.INPUT_METHOD_SUBTYPE_SETTINGS
. | INTERNAL_STORAGE_SETTINGS | android.settings.INTERNAL_STORAGE_SETTINGS
. | LOCATION_SOURCE_SETTINGS | android.settings.LOCATION_SOURCE_SETTINGS
. | MANAGE_APPLICATIONS_SETTINGS | android.settings.MANAGE_APPLICATIONS_SETTINGS
. | MEMORY_APPLICATIONS_SETTINGS | android.settings.MEMORY_APPLICATIONS_SETTINGS
. | MEMORY_CARD_SETTINGS | android.settings.MEMORY_CARD_SETTINGS
. | NETWORK_OPERATOR_SETTINGS | android.settings.NETWORK_OPERATOR_SETTINGS
. | NFCSHARING_SETTINGS | android.settings.NFCSHARING_SETTINGS
. | NFC_SETTINGS | android.settings.NFC_SETTINGS
. | PRIVACY_SETTINGS | android.settings.PRIVACY_SETTINGS
. | QUICK_LAUNCH_SETTINGS | android.settings.QUICK_LAUNCH_SETTINGS
. | SEARCH_SETTINGS | android.settings.SEARCH_SETTINGS
. | SECURITY_SETTINGS | android.settings.SECURITY_SETTINGS
. | SETTINGS | android.settings.SETTINGS
. | SOUND_SETTINGS | android.settings.SOUND_SETTINGS
. | SYNC_SETTINGS | android.settings.SYNC_SETTINGS
. | USER_DICTIONARY_SETTINGS | android.settings.USER_DICTIONARY_SETTINGS
. | WIFI_SETTINGS | android.settings.WIFI_SETTINGS
. | WIRELESS_SETTINGS | android.settings.WIRELESS_SETTINGS
android.phone activity Classes | CallFeaturesSetting | com.android.phone.CallFeaturesSetting | com.android.phone
. | CdmaCallOptions | com.android.phone.CdmaCallOptions | com.android.phone
. | DataUsage | com.android.phone.DataUsage | com.android.phone
. | EmergencyDialer | com.android.phone.EmergencyDialer | com.android.phone
. | EnablelccPinScreen | com.android.phone.EnablelccPinScreen | com.android.phone
. | FdnList | com.android.phone.FdnList | com.android.phone
. | FdnSetting | com.android.phone.FdnSetting | com.android.phone
. | GsmUmtsAdditionalCallOptions | com.android.phone.GsmUmtsAdditionalCallOptions | com.android.phone
. | GsmUmtsCallForwardOptions | com.android.phone.GsmUmtsCallForwardOptions | com.android.phone
. | GsmUmtsCallOptions | com.android.phone.GsmUmtsCallOptions | com.android.phone
. | ManualSelectNetwork | com.android.phone.ManualSelectNetwork | com.android.phone
. | MobileNetworkSettings | com.android.phone.MobileNetworkSettings | com.android.phone
. | NetworkModeSelectionActivity | com.android.phone.NetworkModeSelectionActivity | com.android.phone
. | NetworkSetting | com.android.phone.NetworkSetting | com.android.phone
. | PhonePreference | com.android.phone.PhonePreference | com.android.phone
. | prefernetwork.OperatorSelectActivity | com.android.phone.prefernetwork.OperatorSelectActivity | com.android.phone
. | Settings | com.android.phone.Settings | com.android.phone
. | SimContact | com.android.phone.SimContact | com.android.phone
. | sip.SipSettings | com.android.phone.sip.SipSettings | com.android.phone
android.settings activity Classes | accounts.AddAccountSettings | com.android.settings.accounts.AddAccountSettings | com.android.settings
. | ApnSettings | com.android.settings.ApnSettings | com.android.settings
. | BandMode | com.android.settings.BandMode | com.android.settings
. | BatteryInfo | com.android.settings.BatteryInfo | com.android.settings
. | bluetooth.DevicePickerActivity | com.android.settings.bluetooth.DevicePickerActivity | com.android.settings
. | bluetoothAdvancedSettings | com.android.settings.bluetoothAdvancedSettings | com.android.settings
. | CdmaApnSettings | com.android.settings.CdmaApnSettings | com.android.settings
. | DateTimeSettingsSetupWizard | com.android.settings.DateTimeSettingsSetupWizard | com.android.settings
. | DevelopmentSettings | com.android.settings.DevelopmentSettings | com.android.settings
. | DeviceAdminSettings | com.android.settings.DeviceAdminSettings | com.android.settings
. | Display | com.android.settings.Display | com.android.settings
. | DisplaySettings | com.android.settings.DisplaySettings | com.android.settings
. | DockSettings | com.android.settings.DockSettings | com.android.settings
. | GSensorCalibration | com.android.settings.GSensorCalibration | com.android.settings
. | lccLockSettings | com.android.settings.lccLockSettings | com.android.settings
. | inputmethod.InputMethodAndSebtypeEnablerActivity | com.android.settings.inputmethod.InputMethodAndSebtypeEnablerActivity | com.android.settings
. | LanguageSettings | com.android.settings.LanguageSettings | com.android.settings
. | ManageApplications | com.android.settings.ManageApplications | com.android.settings
. | MediaFormat | com.android.settings.MediaFormat | com.android.settings
. | MediaFormatSD | com.android.settings.MediaFormatSD | com.android.settings
. | ProxySelector | com.android.settings.ProxySelector | com.android.settings
. | quicklaunch.QuickLaunchSettings | com.android.settings.quicklaunch.QuickLaunchSettings | com.android.settings
. | RadioInfo | com.android.settings.RadioInfo | com.android.settings
. | RunningServices | com.android.settings.RunningServices | com.android.settings
. | SecuritySettings | com.android.settings.SecuritySettings | com.android.settings
. | Settings | com.android.settings.Settings | com.android.settings
. | Settings$AccessibilitySettingsActivity | com.android.settings.Settings$AccessibilitySettingsActivity | com.android.settings
. | Settings$AdvancedWifiSettingsActivity | com.android.settings.Settings$AdvancedWifiSettingsActivity | com.android.settings
. | Settings$AndroidBeamSettingsActivity | com.android.settings.Settings$AndroidBeamSettingsActivity | com.android.settings
. | Settings$BluetoothSettingsActivity | com.android.settings.Settings$BluetoothSettingsActivity | com.android.settings
. | Settings$DataUsageSummaryActivity | com.android.settings.Settings$DataUsageSummaryActivity | com.android.settings
. | Settings$DataTimeSettingsActivity | com.android.settings.Settings$DataTimeSettingsActivity | com.android.settings
. | Settings$DeviceInfoSettingsActivity | com.android.settings.Settings$DeviceInfoSettingsActivity | com.android.settings
. | Settings$HDMI3DPlaySettingsActivity | com.android.settings.Settings$HDMI3DPlaySettingsActivity | com.android.settings
. | Settings$InputMethodAndLanguageSettingsActivity | com.android.settings.Settings$InputMethodAndLanguageSettingsActivity | com.android.settings
. | Settings$LocationSettingsActivity | com.android.settings.Settings$LocationSettingsActivity | com.android.settings
. | Settings$ManagerAccountsSettingsActivity | com.android.settings.Settings$ManagerAccountsSettingsActivity | com.android.settings
. | Settings$PowerUsageSummaryActivity | com.android.settings.Settings$PowerUsageSummaryActivity | com.android.settings
. | Settings$PrivacySettingsActivity | com.android.settings.Settings$PrivacySettingsActivity | com.android.settings
. | Settings$SpellCheckersSettingsActivity | com.android.settings.Settings$SpellCheckersSettingsActivity | com.android.settings
. | Settings$StorageUseActivity | com.android.settings.Settings$StorageUseActivity | com.android.settings
. | Settings$TextToSpeechSettingsActivity | com.android.settings.Settings$TextToSpeechSettingsActivity | com.android.settings
. | Settings$VpnSettingsActivity | com.android.settings.Settings$VpnSettingsActivity | com.android.settings
. | Settings$VpnSettingsActivity | com.android.settings.Settings$VpnSettingsActivity | com.android.settings
. | Settings$WifiP2pSettingsActivity | com.android.settings.Settings$WifiP2pSettingsActivity | com.android.settings
. | Settings$WirelessSettingsActivity | com.android.settings.Settings$WirelessSettingsActivity | com.android.settings
. | SettingsSafetyLegalActivity | com.android.settings.SettingsSafetyLegalActivity | com.android.settings
. | SoundSettings | com.android.settings.SoundSettings | com.android.settings
. | TestingSettings | com.android.settings.TestingSettings | com.android.settings
. | UsageStats | com.android.settings.UsageStats | com.android.settings
. | UsbSettings | com.android.settings.UsbSettings | com.android.settings
. | UserDictionarySettings | com.android.settings.UserDictionarySettings | com.android.settings
. | wifi.CWAcountInfo | com.android.settings.wifi.CWAcountInfo | com.android.settings
. | wifi.LanInfo | com.android.settings.wifi.LanInfo | com.android.settings
. | wifi.WifiAPITest | com.android.settings.wifi.WifiAPITest | com.android.settings
. | wifi.ConfigInfo | com.android.settings.wifi.ConfigInfo | com.android.settings
. | wifi.WifiInfo | com.android.settings.wifi.WifiInfo | com.android.settings
. | wifi.WifiSettings | com.android.settings.wifi.WifiSettings | com.android.settings
. | wifi.WifiStatusTest | com.android.settings.wifi.WifiStatusTest | com.android.settings
. | WifiApSettings | com.android.settings.WifiApSettings | com.android.settings