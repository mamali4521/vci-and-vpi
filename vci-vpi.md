# vci-and-vpi
<h1>
  VCI و VPI
  </h1>
  <p>
VPI مخفف عبارت "Virtual Path Identifier" به معنای "مشخص کننده مسیر مجازی" است. این مقدار را معمولاً می‌توانید در تنظیمات مودم خود پیدا کنید. VPI یک مقدار ۸ یا ۱۶ بیتی است که در حالت ۸ بیتی (حالت رایج) دارای ۲۵۶ حالت مختلف بوده و امکان داشتن مقداری بین عدد ۰~۲۵۵ (صفر تا ۲۵۵) را دارد. درحالت ۱۶ بیتی که فعلاً به صورت گسترده استفاده نمی‌شود و در سلول‌های NNI (در بخش بعدی توضیح داده خواهد شد) مورد استفاده قرار می‌گیرد، دارای ۶۵۵۳۶ حالت مختلف بوده و امکان داشتن مقداری بین عدد ۰~۶۵۵۳۵ (صفر تا ۶۵۵۳۵) را دارد.
</p>
  <p>
درواقع مقدار عددی VPI همان مشخص کننده شماره مسیر مجازی است که پاکت‌های داده باید از آن مسیر، مسیر دهی شده و به مقصد برسند. در مثالی که در بخش اول زده شد، VPI همان "نام بزرگ راه" است که فرد باید از آن بگذرد تا به مقصد برسد.
  </p>
همان طور که گفته شد، مسیرهای مجازی خود به کانال‌های مجازی تقسیم می‌شوند. مودم نیاز دارد تا بفهمد از طریق کدام کانال مجازی، در مسیر مجازی مشخص، داده را ارسال کند. این کانال توسط VCI به مودم شناسانده می‌شود. VCI مخفف عبارت "Virtual Channel Identifier" به معنای "مشخص کننده کانال مجازی" بوده و یک مقدار ۱۶ بیتی است. یعنی دارای ۶۵۵۳۶ حالت مختلف بوده و امکان داشتن مقداری بین عدد ۰~۶۵۵۳۵ (صفر تا ۶۵۵۳۵) را دارد.
  <p>.</p>
    <p>
درواقع مقدار عددی VCI همان شماره کانال مجازی را به مودم می‌دهد که داده‌ها باید در مسیر VPIای که انتخاب شده است، مسیر دهی شوند. توسط VCI است که مقصد اصلی مشخص می‌شود. در مثالی که در بخش اول زده شد، VCI همان "شماره باند یک بزرگ راه" است که فرد باید از بین تعداد زیادی از باندهای موجود، از آن بگذرد تا به مقصد اصلی خود برسد.
  </p>
    <p>
دو مقدار VPI و VCI در کنار یکدیگر، مسیر نهایی را مشخص می‌کنند. این دو مقدار باید توسط ISP به کاربر اطلاع داده شوند زیرا بدون فهمیدن این مقادیر، داده‌های ما عملاً به جایی غیر از ISP انتقال داده خواهند شد.
    </p>
  <img src="https://persian-it.com/wp-content/uploads/2022/05/mohammad-reza-esmaeilian.jpg " alt=" motherboard">
