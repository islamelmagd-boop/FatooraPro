# تقرير التسليم والتحديثات - FatooraPro Handover Report

## الهيكل المعتمد
- **المجلد الرئيسي للويب**: `web/`
  - `web/app.js`: المحرك الأساسي للفواتير وحساب الضرائب والإجمالي وتوليد QR Code
  - `web/pricing-tools.js`: أدوات التسعير والخصومات وحساب هوامش الربح
  - `web/merchant-suite.js`: جناح التاجر، كشف الحساب، وتقارير المبيعات
  - `web/index.html`: الصفحة الرئيسية
  - `web/styles.css`: التصميم العصري والمتجاوب
  - `web/sw.js`: Service Worker للعمل أوفلاين
- **مجلد الخادم**: `server/`
  - `server/index.js`: خادم Express مع مسارات الحفظ والمزامنة والطباعة
  - `server/package.json`: حزم الاعتماديات
- **مجلد أندرويد**: `android/`
  - تطبيق جاهز مع أصول الويب المتطابقة في `android/app/src/main/assets/`
