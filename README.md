# الشركة المتحدة للتوابل — موقع الطلب

موقع طلب تفاعلي للمطاعم: دائرة الخلطات التسعة الأكثر طلباً، كتالوج كامل بالأقسام والبحث، وصل يطبع الطلب، والطلب يروح للواتساب.

## الإعدادات (أول السكربت داخل `index.html`)
| الإعداد | الوصف |
|---|---|
| `WHATSAPP` | رقم الطلبات — حالياً `9647711888922` |
| `META_PIXEL_ID` | رقم Meta Pixel من Events Manager (فارغ حالياً) |
| `DELIVERY_FEE` | أجور التوصيل داخل بغداد — حالياً 5,000 |
| `SIZES` | الأوزان 1 / 5 / 10 كغم والمعامل `mult` لكل وزن |
| `PRICE_NOTE` | نص السعر — حالياً "السعر لكل كيلو" |

## أحداث البكسل
`PageView` · `ViewContent` · `AddToCart` · `InitiateCheckout` · `Contact` + `WhatsAppOrder` (custom) مع القيمة ورقم الطلب.

## النشر
ملف واحد `index.html` بالجذر. على Hostinger: Websites → Advanced → Git، اربط هذا الريبو على فرع `main` ومجلد `public_html`.
الصور تنقرا من Google Drive (مجلد products لازم يبقى "أي شخص عنده الرابط") ومن Higgsfield.
