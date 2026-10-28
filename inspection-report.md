# Focused OnStream archive inspection report

ZIPs were read in memory only. No Android code was executed.

## jadx-sources.zip
- Entries: 10814
- Expanded size: 49,248,288 bytes
- Root folders: sources (8279), resources (2535)
- Decompiled Java/Kotlin files: 8279
- Most populated source folders: sources/co/notix (788), sources/com/google (694), sources/j$/util (385), sources/com/maertsno (209), sources/j$/time (116), sources/androidx/datastore (67), sources/androidx/lifecycle (59), sources/android/support (52), sources/androidx/mediarouter (46), sources/java/util (36), sources/androidx/appcompat (26), sources/androidx/work (23), sources/kotlin/jvm (19), sources/androidx/media (9), sources/androidx/core (7), sources/android/media (6), sources/androidx/recyclerview (5), sources/codes/side (3), sources/androidx/databinding (3), sources/androidx/constraintlayout (3), sources/android/window (2), sources/androidx/profileinstaller (2), sources/androidx/versionedparcelable (2), sources/U6/a.java (1)

### Android manifest
- Package: com.maertsno.m
- Version: 1.1.7; code 19
- Android SDK min/target: 23 / 35
- App label: @string/app_name_onstream
- Application class: com.maertsno.m.App
- activity: com.maertsno.m.ui.main.MainActivity exported=true [LAUNCHER]
  actions: android.intent.action.MAIN
- activity: com.maertsno.m.ui.player.PlayerActivity exported=false
- activity: com.maertsno.m.ui.player.MoviePlayerActivity exported=false
- activity: com.maertsno.m.ui.trailer.TrailerActivity exported=false
- service: com.maertsno.m.service.AppMessagingService exported=false
  actions: com.google.firebase.MESSAGING_EVENT
- provider: androidx.core.content.FileProvider exported=false
- receiver: com.google.android.gms.cast.framework.media.MediaIntentReceiver exported=false
- service: com.google.android.gms.cast.framework.media.MediaNotificationService exported=false
- service: com.google.android.gms.cast.framework.ReconnectionService exported=false
- activity: com.google.android.gms.auth.api.signin.internal.SignInHubActivity exported=false
- service: com.google.android.gms.auth.api.signin.RevocationBoundService exported=true
- service: com.google.firebase.components.ComponentDiscoveryService exported=false
- service: co.notix.push.firebase.NotixFirebaseMessagingService exported=false
  actions: com.google.firebase.MESSAGING_EVENT
- activity: co.notix.push.permissions.NotificationsPermissionActivity exported=false
- activity: co.notix.push.NotificationClickHandlerActivity exported=false
- activity: co.notix.interstitial.InterstitialActivity exported=false
- activity: co.notix.interstitial.WebViewInterstitialActivity exported=false
- activity: co.notix.lsi.LockScreenInterstitialActivity exported=false
- activity: co.notix.appopen.AppOpenActivity exported=false
- provider: androidx.startup.InitializationProvider exported=false
- receiver: com.google.firebase.iid.FirebaseInstanceIdReceiver exported=true
  actions: com.google.android.c2dm.intent.RECEIVE
- service: com.google.firebase.messaging.FirebaseMessagingService exported=false
  actions: com.google.firebase.MESSAGING_EVENT
- receiver: com.google.android.gms.measurement.AppMeasurementReceiver exported=false
- service: com.google.android.gms.measurement.AppMeasurementService exported=false
- service: com.google.android.gms.measurement.AppMeasurementJobService exported=false
- activity: com.google.android.gms.common.api.GoogleApiActivity exported=false
- service: com.google.firebase.sessions.SessionLifecycleService exported=false
- provider: com.google.firebase.provider.FirebaseInitProvider exported=false
- service: androidx.work.impl.background.systemalarm.SystemAlarmService exported=false
- service: androidx.work.impl.background.systemjob.SystemJobService exported=true
- service: androidx.work.impl.foreground.SystemForegroundService exported=false
- receiver: androidx.work.impl.utils.ForceStopRunnable$BroadcastReceiver exported=false
- receiver: androidx.work.impl.background.systemalarm.ConstraintProxy$BatteryChargingProxy exported=false
  actions: android.intent.action.ACTION_POWER_CONNECTED, android.intent.action.ACTION_POWER_DISCONNECTED
- receiver: androidx.work.impl.background.systemalarm.ConstraintProxy$BatteryNotLowProxy exported=false
  actions: android.intent.action.BATTERY_OKAY, android.intent.action.BATTERY_LOW
- receiver: androidx.work.impl.background.systemalarm.ConstraintProxy$StorageNotLowProxy exported=false
  actions: android.intent.action.DEVICE_STORAGE_LOW, android.intent.action.DEVICE_STORAGE_OK
- receiver: androidx.work.impl.background.systemalarm.ConstraintProxy$NetworkStateProxy exported=false
  actions: android.net.conn.CONNECTIVITY_CHANGE
- receiver: androidx.work.impl.background.systemalarm.RescheduleReceiver exported=false
  actions: android.intent.action.BOOT_COMPLETED, android.intent.action.TIME_SET, android.intent.action.TIMEZONE_CHANGED
- receiver: androidx.work.impl.background.systemalarm.ConstraintProxyUpdateReceiver exported=false
  actions: androidx.work.impl.background.systemalarm.UpdateProxies
- receiver: androidx.work.impl.diagnostics.DiagnosticsReceiver exported=true
  actions: androidx.work.diagnostics.REQUEST_DIAGNOSTICS
- service: androidx.room.MultiInstanceInvalidationService exported=false
- service: com.google.android.datatransport.runtime.backends.TransportBackendDiscovery exported=false
- receiver: androidx.profileinstaller.ProfileInstallReceiver exported=true
  actions: androidx.profileinstaller.action.INSTALL_PROFILE, androidx.profileinstaller.action.SKIP_FILE, androidx.profileinstaller.action.SAVE_PROFILE, androidx.profileinstaller.action.BENCHMARK_OPERATION
- service: com.google.android.datatransport.runtime.scheduling.jobscheduling.JobInfoSchedulerService exported=false
- receiver: com.google.android.datatransport.runtime.scheduling.jobscheduling.AlarmManagerSchedulerBroadcastReceiver exported=false
- Permissions: android.permission.INTERNET, android.permission.REQUEST_INSTALL_PACKAGES, android.permission.WRITE_EXTERNAL_STORAGE, android.permission.POST_NOTIFICATIONS, android.permission.FOREGROUND_SERVICE, android.permission.ACCESS_NETWORK_STATE, android.permission.VIBRATE, android.permission.USE_FULL_SCREEN_INTENT, android.permission.WAKE_LOCK, com.google.android.c2dm.permission.RECEIVE, com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE, com.google.android.gms.permission.AD_ID, android.permission.ACCESS_ADSERVICES_ATTRIBUTION, android.permission.ACCESS_ADSERVICES_AD_ID, android.permission.RECEIVE_BOOT_COMPLETED, com.maertsno.m.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION

### Relevant app text (first 80 matches)
- Matches: 2556
- abc_search_hint = 搜尋…
- abc_searchview_description_clear = 清除查詢
- abc_searchview_description_query = 搜尋查詢
- abc_searchview_description_search = 搜尋
- abc_searchview_description_submit = 提交查詢
- abc_searchview_description_voice = 語音搜尋
- cast_expanded_controller_live_stream_indicator = 直播
- cast_expanded_controller_loading = 載入中…
- cast_stop_live_stream = 停止直播
- cast_tracks_chooser_dialog_subtitles = 字幕
- common_google_play_services_update_button = 更新
- common_google_play_services_update_text = 您必須更新 Google Play 服務，才能執行「%1$s」。
- common_google_play_services_update_title = 更新 Google Play 服務
- common_google_play_services_wear_update_text = 必須使用新版 Google Play 服務。該服務稍後就會自動更新。
- error_a11y_label = 錯誤：無效
- error_icon_content_description = 錯誤
- exo_download_completed = 下載完成
- exo_download_description = 下載
- exo_download_downloading = 下載中
- exo_download_failed = 無法下載
- exo_download_notification_channel_name = 下載
- exo_download_paused = 已暫停下載
- exo_download_paused_for_network = 系統會等到連上網路後再開始下載
- exo_download_paused_for_wifi = 系統會等到連上 Wi-Fi 後再開始下載
- exo_download_removing = 正在移除下載內容
- mr_chooser_searching = 正在尋找裝置
- mr_user_route_category_name = 裝置
- search_menu_title = 搜尋
- searchview_clear_text_content_description = 清除文字
- searchview_navigation_content_description = 返回
- abc_search_hint = جستجو…‏
- abc_searchview_description_clear = پاک کردن پُرسمان
- abc_searchview_description_query = درخواست جستجو
- abc_searchview_description_search = جستجو
- abc_searchview_description_submit = ارسال پُرسمان
- abc_searchview_description_voice = جستجوی گفتاری
- cast_expanded_controller_live_stream_indicator = جاری‌سازی زنده
- cast_expanded_controller_loading = درحال بار کردن…
- cast_stop_live_stream = توقف پخش جریانی زنده
- cast_tracks_chooser_dialog_subtitles = زیرنویس‌ها
- common_google_play_services_update_button = به‌روزرسانی
- common_google_play_services_update_text = ‏تاز مانی که «خدمات Google Play» را به‌روزرسانی نکنید، %1$s اجرا نمی‌شود.
- common_google_play_services_update_title = ‏‫به‌روزرسانی «خدمات Google Play»
- common_google_play_services_wear_update_text = ‏نسخه جدید «خدمات Google Play» نیاز است. به‌زودی به‌طور خودکار به‌روزرسانی می‌شود.
- error_a11y_label = خطا: نامعتبر
- error_icon_content_description = خطا
- exo_download_completed = بارگیری کامل شد
- exo_download_description = بارگیری
- exo_download_downloading = درحال بارگیری
- exo_download_failed = بارگیری نشد
- exo_download_notification_channel_name = بارگیری‌ها
- exo_download_paused = بارگیری‌ها موقتاً متوقف شد
- exo_download_paused_for_network = بارگیری‌ها درانتظار شبکه است
- exo_download_paused_for_wifi = بارگیری‌ها در انتظار Wi-Fi است
- exo_download_removing = حذف بارگیری‌ها
- mr_chooser_searching = درحال پیدا کردن دستگاه‌ها
- mr_user_route_category_name = دستگاه‌ها
- search_menu_title = جستجو
- searchview_clear_text_content_description = پاک کردن نوشتار
- searchview_navigation_content_description = برگشتن
- abc_search_hint = Buscar…
- abc_searchview_description_clear = Borrar consulta
- abc_searchview_description_query = Consulta de búsqueda
- abc_searchview_description_search = Buscar
- abc_searchview_description_submit = Enviar consulta
- abc_searchview_description_voice = Búsqueda por voz
- cast_expanded_controller_live_stream_indicator = Streaming en directo
- cast_expanded_controller_loading = Cargando…
- cast_stop_live_stream = Detener streaming en directo
- cast_tracks_chooser_dialog_subtitles = Subtítulos
- common_google_play_services_update_button = Actualizar
- common_google_play_services_update_text = %1$s no funcionará hasta que no actualices Servicios de Google Play.
- common_google_play_services_update_title = Actualiza Servicios de Google Play
- common_google_play_services_wear_update_text = Se necesita una nueva versión de Servicios de Google Play. Se actualizará en breve.
- error_a11y_label = Error: no válida
- error_icon_content_description = Error
- exo_download_completed = Descarga de archivos completado
- exo_download_description = Descargar
- exo_download_downloading = Descargando
- exo_download_failed = No se ha podido descargar

## apktool-output.zip
- Entries: 8513
- Expanded size: 71,183,433 bytes
- Root folders: smali (5605), res (2368), smali_classes2 (386), unknown (140), lib (6), original (4), (root) (2), assets (2)
- Relevant resource/Smali paths: 294
  - AndroidManifest_already_existing_so_2nd_file.xml
  - lib/arm64-v8a/libplayer.so
  - lib/armeabi-v7a/libplayer_already_existing_so_2nd_file.so
  - original/AndroidManifest.xml
  - res/color/abc_search_url_text.xml
  - res/color/color_background_season.xml
  - res/drawable/abc_ic_go_search_api_material.xml
  - res/drawable/abc_ic_search_api_material.xml
  - res/drawable/abc_ic_voice_search_api_material.xml
  - res/drawable/abc_textfield_search_material.xml
  - res/drawable/background_middle_season.xml
  - res/drawable/background_player.xml
  - res/drawable/background_recommend_player.xml
  - res/drawable/background_season_bottom_corner.xml
  - res/drawable/background_season_spinner.xml
  - res/drawable/background_season_top_corner.xml
  - res/drawable/background_selected_player.xml
  - res/drawable/background_unselected_season.xml
  - res/drawable/bg_search.xml
  - res/drawable/cast_ic_notification_stop_live_stream.xml
  - res/drawable/exo_ic_subtitle_off.xml
  - res/drawable/exo_ic_subtitle_on.xml
  - res/drawable/ic_call_answer_video.xml
  - res/drawable/ic_call_answer_video_low.xml
  - res/drawable/ic_player_selected.xml
  - res/drawable/ic_player_unselected.xml
  - res/drawable/ic_search_black_24.xml
  - res/drawable/ic_subtitle.xml
  - res/drawable-anydpi-v24/ic_episodes.xml
  - res/drawable-anydpi-v24/ic_play_episode.xml
  - res/drawable-anydpi-v24/ic_search.xml
  - res/drawable-hdpi/abc_ic_commit_search_api_mtrl_alpha_already_existing_so_4th_file.png
  - res/drawable-hdpi/abc_textfield_search_activated_mtrl_alpha.9_already_existing_so_3rd_file.png
  - res/drawable-hdpi/abc_textfield_search_default_mtrl_alpha.9_already_existing_so_3rd_file.png
  - res/drawable-hdpi/ic_episodes_already_existing_so_4th_file.png
  - res/drawable-hdpi/ic_play_episode_already_existing_so_4th_file.png
  - res/drawable-hdpi/ic_search_already_existing_so_4th_file.png
  - res/drawable-ldpi/ic_episodes_already_existing_so_6th_file.png
  - res/drawable-ldpi/ic_play_episode_already_existing_so_6th_file.png
  - res/drawable-ldpi/ic_search_already_existing_so_6th_file.png
  - res/drawable-mdpi/abc_ic_commit_search_api_mtrl_alpha_already_existing_so_3rd_file.png
  - res/drawable-mdpi/abc_textfield_search_activated_mtrl_alpha.9_already_existing_so_4th_file.png
  - res/drawable-mdpi/abc_textfield_search_default_mtrl_alpha.9_already_existing_so_4th_file.png
  - res/drawable-mdpi/ic_episodes_already_existing_so_5th_file.png
  - res/drawable-mdpi/ic_play_episode_already_existing_so_5th_file.png
  - res/drawable-mdpi/ic_search_already_existing_so_5th_file.png
  - res/drawable-xhdpi/abc_ic_commit_search_api_mtrl_alpha.png
  - res/drawable-xhdpi/abc_textfield_search_activated_mtrl_alpha.9_already_existing_so_2nd_file.png
  - res/drawable-xhdpi/abc_textfield_search_default_mtrl_alpha.9_already_existing_so_2nd_file.png
  - res/drawable-xhdpi/ic_episodes_already_existing_so_3rd_file.png
  - res/drawable-xhdpi/ic_play_episode_already_existing_so_3rd_file.png
  - res/drawable-xhdpi/ic_search_already_existing_so_3rd_file.png
  - res/drawable-xxhdpi/abc_ic_commit_search_api_mtrl_alpha_already_existing_so_2nd_file.png
  - res/drawable-xxhdpi/abc_textfield_search_activated_mtrl_alpha.9.png
  - res/drawable-xxhdpi/abc_textfield_search_default_mtrl_alpha.9.png
  - res/drawable-xxhdpi/ic_episodes_already_existing_so_2nd_file.png
  - res/drawable-xxhdpi/ic_play_episode_already_existing_so_2nd_file.png
  - res/drawable-xxhdpi/ic_search_already_existing_so_2nd_file.png
  - res/drawable-xxxhdpi/ic_episodes.png
  - res/drawable-xxxhdpi/ic_play_episode.png
  - res/drawable-xxxhdpi/ic_search.png
  - res/layout/abc_search_dropdown_item_icons_2line.xml
  - res/layout/abc_search_view.xml
  - res/layout/activity_main.xml
  - res/layout/activity_movie_player.xml
  - res/layout/activity_player.xml
  - res/layout/bottom_sheet_player_subtitle.xml
  - res/layout/bottom_sheet_select_player.xml
  - res/layout/bottom_sheet_select_subtitle.xml
  - res/layout/exo_player_control_view.xml
  - res/layout/exo_player_view.xml
  - res/layout/exo_styled_player_control_view.xml
  - res/layout/exo_styled_player_view.xml
  - res/layout/fragment_episode_list.xml
  - res/layout/fragment_movie_detail.xml
  - res/layout/fragment_movie_overview.xml
  - res/layout/fragment_movies.xml
  - res/layout/fragment_search.xml
  - res/layout/item_episode.xml
  - res/layout/item_episode_playlist.xml

## Cross-source findings
- JADX source/resource text files scanned in full: 8276
- Most relevant likely application files (third-party framework packages omitted):
### sources/com/maertsno/m/ui/player/PlayerActivity.java (65,285 bytes; relevance 88)
  - import com.maertsno.exoplayer.StyledPlayerView;
  - import com.maertsno.exoplayer.SubtitleView;
  -         abstractC0263e.X.setText(getString(R.string.format_sub_delay, Float.valueOf(0.0f)));
  -             Toast.makeText(getApplicationContext(), R.string.msg_unknown_error, 0).show();
  -         StyledPlayerView styledPlayerView = abstractC0263e.f5271T;
### sources/com/maertsno/m/ui/player/MoviePlayerActivity.java (50,986 bytes; relevance 75)
  - import com.maertsno.exoplayer.StyledPlayerView;
  - import com.maertsno.exoplayer.SubtitleView;
  -             Toast.makeText(getApplicationContext(), R.string.msg_no_playable_sources, 0).show();
  -         StyledPlayerView styledPlayerView = abstractC0258c.f5241T;
  -             styledPlayerView.setPlayer(a0());
### sources/com/maertsno/m/DataBinderMapperImpl.java (27,029 bytes; relevance 69)
  -         sparseIntArray.put(R.layout.activity_main, 1);
  -         sparseIntArray.put(R.layout.activity_movie_player, 2);
  -         sparseIntArray.put(R.layout.activity_player, 3);
  -         sparseIntArray.put(R.layout.activity_trailer, 4);
  -         sparseIntArray.put(R.layout.bottom_sheet_common_error, 5);
### sources/G6/J.java (6,059 bytes; relevance 36)
  - import com.maertsno.exoplayer.StyledPlayerView;
  - import com.maertsno.exoplayer.SubtitleView;
  -     public final /* synthetic */ StyledPlayerView f2428c;
  -     public J(StyledPlayerView styledPlayerView) {
  -         this.f2428c = styledPlayerView;
### sources/G6/I.java (2,483 bytes; relevance 25)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -     public final /* synthetic */ StyledPlayerView f2425a;
  -     public I(StyledPlayerView styledPlayerView) {
  -         this.f2425a = styledPlayerView;
  -         StyledPlayerView styledPlayerView = this.f2425a;
### sources/p083i7/C0997j.java (5,835 bytes; relevance 21)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -         int i10 = R.string.label_mode_width;
  -                 StyledPlayerView styledPlayerView = (StyledPlayerView) obj3;
  -                 int resizeMode = styledPlayerView.getResizeMode();
  -                         i10 = R.string.label_mode_height;
### sources/G6/C.java (56,824 bytes; relevance 19)
  -         int resourceId = R.layout.exo_styled_player_control_view;
  -                 resourceId = typedArrayObtainStyledAttributes.getResourceId(6, R.layout.exo_styled_player_control_view);
  -         C0164x c0164x = new C0164x(this, new String[]{resources.getString(R.string.exo_controls_playback_speed), resources.getString(R.string.exo_track_selection_title_audio)}, new Drawable[]{resources.getDrawable(R.drawable.exo_styled_controls_speed
  -         FrameLayout frameLayout = (FrameLayout) LayoutInflater.from(context).inflate(R.layout.exo_styled_settings_list, (ViewGroup) null);
  -         resources.getString(R.string.exo_controls_cc_enabled_description);
### sources/V5/c.java (37,645 bytes; relevance 14)
  -         String string = (i9 & 2) != 0 ? resources.getString(R.string.exo_track_role_alternate) : "";
  -             string = q(string, resources.getString(R.string.exo_track_role_supplementary));
  -             string = q(string, resources.getString(R.string.exo_track_role_commentary));
  -         return (i10 & 1088) != 0 ? q(string, resources.getString(R.string.exo_track_role_closed_captions)) : string;
  -             strH = q(i(n9), (i12 == -1 || i11 == -1) ? "" : resources.getString(R.string.exo_track_resolution, Integer.valueOf(i12), Integer.valueOf(i11)), i9 != -1 ? resources.getString(R.string.exo_track_bitrate, Float.valueOf(i9 / 1000000.0f)) : "
### sources/p089j4/e.java (7,655 bytes; relevance 13)
  -             FrameLayout frameLayout = (FrameLayout) View.inflate(getContext(), R.layout.design_bottom_sheet_dialog, null);
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -     public final void setContentView(int i9) {
  -         super.setContentView(h(null, i9, null));
### sources/co/notix/ab.java (5,118 bytes; relevance 12)
  -         String string = ((d9) this.f12003a).a().getString(R.string.notix_public_app_name);
  -         kotlin.jvm.internal.h.d(string, "context.getString(R.string.notix_public_app_name)");
  -         String string = contextA.getString(R.string.notix_public_app_name);
  -         kotlin.jvm.internal.h.d(string, "context.getString(R.string.notix_public_app_name)");
  -         String string2 = contextA.getString(R.string.notix_public_app_id);
### sources/com/maertsno/exoplayer/StyledPlayerView.java (30,534 bytes; relevance 12)
  - package com.maertsno.exoplayer;
  - public class StyledPlayerView extends FrameLayout {
  -     public StyledPlayerView(Context context, AttributeSet attributeSet) {
  -                 int resourceId2 = typedArrayObtainStyledAttributes.getResourceId(14, R.layout.exo_styled_player_view);
  -             i13 = R.layout.exo_styled_player_view;
### sources/com/maertsno/m/ui/main/MainActivity.java (20,974 bytes; relevance 12)
  -         super.onCreate(bundle);
  -         g gVarC = c.c(this, R.layout.activity_main);
  -         h.d(gVarC, "setContentView(...)");
  -             throw new IllegalStateException("NavController is not available before onCreate()");
  -         w1 w1Var = (w1) c.b(layoutInflaterFrom, R.layout.layout_snackbar, null, false);
### sources/com/maertsno/m/ui/update/UpdateFragment.java (13,540 bytes; relevance 12)
  -                             updateFragment.p0(new y(R.string.msg_permission_denied), true);
  -                             updateFragment2.p0(new y(R.string.msg_permission_denied), true);
  -                             updateFragment.p0(new y(R.string.msg_permission_denied), true);
  -                             updateFragment2.p0(new y(R.string.msg_permission_denied), true);
  -         return R.layout.fragment_update;
### sources/p030d/k.java (15,990 bytes; relevance 12)
  -     public void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -     public void setContentView(int i9) {
  -         super.setContentView(i9);
  -     public void setContentView(@SuppressLint({"UnknownNullness", "MissingNullability"}) View view) {
### sources/p030d/l.java (5,000 bytes; relevance 12)
  -     public void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -     public void setContentView(int i9) {
  -         super.setContentView(i9);
  -     public void setContentView(View view) {
### sources/B3/o.java (7,742 bytes; relevance 11)
  -             return resources.getString(R.string.common_google_play_services_install_text, strA);
  -             return G3.b.f(context) ? resources.getString(R.string.common_google_play_services_wear_update_text) : resources.getString(R.string.common_google_play_services_update_text, strA);
  -             return resources.getString(R.string.common_google_play_services_enable_text, strA);
  -             return resources.getString(R.string.common_google_play_services_unsupported_text, strA);
  -                 return resources.getString(R.string.common_google_play_services_updating_text, strA);
### sources/p052f2/E.java (77,320 bytes; relevance 10)
  -         L.a("goog.exo.exoplayer");
  -             a.A("ExoPlayerImpl", "Init " + Integer.toHexString(System.identityHashCode(this)) + " [ExoPlayerLib/2.18.2] [" + y.f18904e + "]");
  -         sb.append(" [ExoPlayerLib/2.18.2] [");
  -         a.A("ExoPlayerImpl", sb.toString());
  -                 a.P("ExoPlayerImpl", "SurfaceTextureListener already unset or replaced.");
### sources/co/notix/appopen/AppOpenActivity.java (10,587 bytes; relevance 9)
  - public final class AppOpenActivity extends Activity {
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -         setContentView(R.layout.notix_activity_appopen);
### sources/com/maertsno/exoplayer/TrackSelectionView.java (8,644 bytes; relevance 9)
  - package com.maertsno.exoplayer;
  -         CheckedTextView checkedTextView = (CheckedTextView) layoutInflaterFrom.inflate(R.layout.simple_list_item_single_choice, (ViewGroup) this, false);
  -         checkedTextView.setText(co.notix.R.string.exo_track_selection_none);
  -         addView(layoutInflaterFrom.inflate(co.notix.R.layout.exo_list_divider, (ViewGroup) this, false));
  -         CheckedTextView checkedTextView2 = (CheckedTextView) layoutInflaterFrom.inflate(R.layout.simple_list_item_single_choice, (ViewGroup) this, false);
### sources/com/maertsno/m/App.java (5,831 bytes; relevance 9)
  -     public final void onCreate() throws Throwable {
  -         super.onCreate();
  -             String string = getString(R.string.default_channel_name);
  -             String string2 = getString(R.string.default_channel_description);
  -             NotificationChannel notificationChannelC = b.c(getString(R.string.default_notification_channel_id), string);
### sources/p075i/w.java (76,592 bytes; relevance 9)
  -             viewGroup = this.f19092e0 ? (ViewGroup) layoutInflaterFrom.inflate(co.notix.R.layout.abc_screen_simple_overlay_action_mode, (ViewGroup) null) : (ViewGroup) layoutInflaterFrom.inflate(co.notix.R.layout.abc_screen_simple, (ViewGroup) null);
  -             viewGroup = (ViewGroup) layoutInflaterFrom.inflate(co.notix.R.layout.abc_dialog_title_material, (ViewGroup) null);
  -             viewGroup = (ViewGroup) LayoutInflater.from(typedValue.resourceId != 0 ? new c(context, typedValue.resourceId) : context).inflate(co.notix.R.layout.abc_screen_toolbar, (ViewGroup) null);
  -         this.f19100l.setContentView(viewGroup);
### sources/p075i/y.java (4,266 bytes; relevance 9)
  -     public void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -     public void setContentView(int i9) {
  -     public void setContentView(View view) {
  -     public void setContentView(View view, ViewGroup.LayoutParams layoutParams) {
### sources/L6/m.java (24,098 bytes; relevance 8)
  -                 P retrofit = (P) nVar.j.get();
  -                 kotlin.jvm.internal.h.e(retrofit, "retrofit");
  -                 Object objB = retrofit.b(p175s6.a.class);
  -                 A okHttpClient = (A) nVar.f4174i.get();
  -                 kotlin.jvm.internal.h.e(okHttpClient, "okHttpClient");
### sources/M6/b.java (4,862 bytes; relevance 8)
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -         AbstractC0298w abstractC0298w = (AbstractC0298w) c.b(layoutInflaterFrom, R.layout.confirm_dialog, null, false);
  -         setContentView(abstractC0298w.f7790s);
### sources/com/maertsno/m/ui/trailer/TrailerActivity.java (10,219 bytes; relevance 8)
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -         g gVarC = W.c.c(this, R.layout.activity_trailer);
  -         h.d(gVarC, "setContentView(...)");
### sources/p036d5/h.java (33,965 bytes; relevance 8)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -         ((StyledPlayerView) this.f16762b).setDefaultArtwork(drawable);
  -             dialogInterfaceOnCancelListenerC1194q.f20535F0.setContentView(viewB0);
### sources/p208x3/e.java (8,579 bytes; relevance 8)
  -             string = resources.getString(co.notix.R.string.common_google_play_services_install_button);
  -             string = i9 != 3 ? resources.getString(R.string.ok) : resources.getString(co.notix.R.string.common_google_play_services_enable_button);
  -             string = resources.getString(co.notix.R.string.common_google_play_services_update_button);
  -             strE = context.getResources().getString(co.notix.R.string.common_google_play_services_notification_ticker);
  -                 nVar.f901b.add(new h(IconCompat.b(null, "", co.notix.R.drawable.common_full_open_on_phone), resources.getString(co.notix.R.string.common_open_on_phone), pendingIntent, new Bundle(), null, null, true, true));
### sources/s7/m.java (12,255 bytes; relevance 8)
  -                     R6.y yVar = new R6.y(R.string.msg_no_playable_sources);
  -                     R6.y yVar2 = new R6.y(R.string.msg_unknown_error);
  -                 strS = selectPlayerFragment2.s(R.string.label_none);
  -                 String strS2 = selectPlayerFragment3.s(R.string.title_download_tool);
  -                 String string2 = mainActivity.getResources().getString(R.string.message_external_player);
### sources/z7/d.java (7,974 bytes; relevance 8)
  -                                 y yVar = new y(R.string.msg_sources_not_found);
  -                                             String strS = subtitleSelectFragment.s(R.string.title_download_tool);
  -                                             String string = mainActivity.getResources().getString(R.string.message_download_tool);
  -                                             String string2 = mainActivity.getResources().getString(R.string.label_cancel);
  -                                             String string3 = mainActivity.getResources().getString(R.string.title_install);
### sources/D/f.java (2,036 bytes; relevance 7)
  - public abstract class f extends Activity implements InterfaceC0552v, InterfaceC0318k {
  -     public void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
### sources/co/notix/push/NotificationClickHandlerActivity.java (2,552 bytes; relevance 7)
  - public final class NotificationClickHandlerActivity extends Activity {
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
### sources/co/notix/push/permissions/NotificationsPermissionActivity.java (1,226 bytes; relevance 7)
  - public final class NotificationsPermissionActivity extends Activity {
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
### sources/co/notix/zb.java (3,865 bytes; relevance 7)
  - public abstract class zb extends Activity {
  -     public final void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
### sources/com/maertsno/m/ui/settings/general/GeneralSettingsFragment.java (11,237 bytes; relevance 7)
  -         return R.layout.fragment_general_settings;
  -         ArrayAdapter<CharSequence> arrayAdapterCreateFromResource = ArrayAdapter.createFromResource(view.getContext(), R.array.typeface, android.R.layout.simple_spinner_item);
  -         arrayAdapterCreateFromResource.setDropDownViewResource(R.layout.item_spinner_setting);
  -         ArrayAdapter<CharSequence> arrayAdapterCreateFromResource2 = ArrayAdapter.createFromResource(view.getContext(), R.array.quality, android.R.layout.simple_spinner_item);
  -         arrayAdapterCreateFromResource2.setDropDownViewResource(R.layout.item_spinner_setting);
### sources/p052f2/K.java (141,848 bytes; relevance 7)
  -         HandlerThread handlerThread = new HandlerThread("ExoPlayer:Playback", -16);
  -                 a.u("ExoPlayerImplInternal", "Disable failed.", e9);
  -                         a.u("ExoPlayerImplInternal", "Reset failed.", e10);
  -         a.u("ExoPlayerImplInternal", "Playback error", c0916m);
  -                 a.Q("ExoPlayerImplInternal", "Recoverable renderer error", e);
### sources/p075i/AbstractActivityC0986h.java (34,523 bytes; relevance 7)
  -     public final void setContentView(int i9) {
  -     public void setContentView(View view) {
  -     public final void setContentView(View view, ViewGroup.LayoutParams layoutParams) {
### sources/p075i/DialogInterfaceC0985g.java (12,248 bytes; relevance 7)
  -     public void onCreate(Bundle bundle) {
  -         super.onCreate(bundle);
  -         c0983e.f19013b.setContentView(c0983e.f19035y);
### sources/p083i7/AbstractActivityC0989b.java (4,976 bytes; relevance 7)
  -     public void onCreate(Bundle bundle) {
  -                 super.onCreate(bundle);
  -                 super.onCreate(bundle);
### sources/C7/q.java (21,545 bytes; relevance 6)
  -                     i10 = R.string.label_newest;
  -                     i10 = R.string.label_trending;
  -                     i10 = R.string.label_popular;
  -                     fVar.a(R.string.title_movie);
  -                     fVar.a(R.string.title_tv_series);
### sources/D7/t.java (9,360 bytes; relevance 6)
  -                 contentValues.put("_display_name", application.getString(R.string.app_name_onstream) + ".apk");
  -                         yVar = new y(R.string.msg_unknown_error);
  -                 vVar.f1123k = Environment.getExternalStoragePublicDirectory(Environment.DIRECTORY_DOWNLOADS).getAbsolutePath() + "/" + application.getString(R.string.app_name_onstream) + ".apk";
  -                         yVar2 = new y(R.string.msg_unknown_error);
  -                 yVar = new y(R.string.msg_unknown_error);
### sources/G6/H.java (22,366 bytes; relevance 6)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -                 StyledPlayerView styledPlayerView = ((J) b10).f2428c;
  -                 styledPlayerView.j();
  -                 K k9 = styledPlayerView.f16407q;
### sources/L6/q.java (1,131 bytes; relevance 6)
  -     public void onCreate() {
  -         super.onCreate();
### sources/N6/AbstractC0258c.java (3,494 bytes; relevance 6)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -     public final StyledPlayerView f5241T;
  -     public AbstractC0258c(View view, MaterialButton materialButton, MaterialButton materialButton2, MaterialButton materialButton3, Chip chip, Chip chip2, ChipGroup chipGroup, Chip chip3, Chip chip4, Chip chip5, AppCompatImageView appCompatImageView,
  -         this.f5241T = styledPlayerView;
### sources/N6/AbstractC0263e.java (4,262 bytes; relevance 6)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -     public final StyledPlayerView f5271T;
  -     public AbstractC0263e(View view, MaterialButton materialButton, MaterialButton materialButton2, MaterialButton materialButton3, Chip chip, Chip chip2, ChipGroup chipGroup, Chip chip3, Chip chip4, Chip chip5, AppCompatImageView appCompatImageView,
  -         this.f5271T = styledPlayerView;
### sources/N6/C0261d.java (4,019 bytes; relevance 6)
  - import com.maertsno.exoplayer.StyledPlayerView;
  -         StyledPlayerView styledPlayerView = (StyledPlayerView) objArrZ[1];
  -         super(view, materialButton, materialButton2, materialButton3, chip, chip2, chipGroup, chip3, chip4, chip5, appCompatImageView, materialButton4, materialButton5, frameLayout, frameLayout2, frameLayout3, styledPlayerView, (TextView) objArrZ[15]

### Network hostnames found (query strings excluded)
- schemas.android.com (64 references)
- issuetracker.google.com (8 references)
- firebase.google.com (8 references)
- www.w3.org (5 references)
- www.googleadservices.com (5 references)
- app-measurement.com (4 references)
- example.com (4 references)
- exoplayer.dev (2 references)
- dashif.org (2 references)
- ns.adobe.com (2 references)
- x (2 references)
- www.youtube.com (2 references)
- developer.android.com (2 references)
- www.googleapis.com (2 references)
- goo.gl (2 references)
- base.url (1 references)
- firebase-settings.crashlytics.com (1 references)
- youtrack.jetbrains.com (1 references)
- firebaseremoteconfigrealtime.googleapis.com (1 references)
- schemas.microsoft.com (1 references)
- plus.google.com (1 references)
- aomedia.org (1 references)
- developer.apple.com (1 references)
- default.url (1 references)
- pagead2.googlesyndication.com (1 references)
- firebaseremoteconfig.googleapis.com (1 references)
- firebaseinstallations.googleapis.com (1 references)
- accounts.google.com (1 references)
- www.google.com (1 references)
- google.com (1 references)

### Code/library indicators
- subtitles: 58 files
- player: 54 files
- Android screens: 52 files
- stream formats: 23 files
- Firebase: 20 files
- catalog/API: 18 files
- network: 6 files

