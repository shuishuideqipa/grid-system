栅格系统：可以根据用户的行为以及设备环境(系统平台，屏幕尺寸，屏幕定向)进行响应及调整。无论用户在手机，平板还是pc上能够自动切换分辨，图片的尺寸及相关脚本，可以适应不同设备，一个网站可以兼容多个终端。

用法：通过媒体查询media来实现栅格系统,
/* 浏览器宽度小于等于768px时， 内部的CSS生效 * */
@media (max-width: 768px) {
body { font-size: 16px; }
}

/* 浏览器窗口宽度大于等于992时，内部CSS生效 */
@media (min-width: 992px) {
body { font-size: 16px; }

/* 浏览器窗口宽度大于等于1200时，内部CSS生效 */
@media (min-width: 1200px) {
body { font-size: 16px; }