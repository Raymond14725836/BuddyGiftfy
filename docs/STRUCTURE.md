# แผนผังไฟล์โครงการ

เริ่มอ่านภาพรวมและบทบาทของผู้จัดทำที่ [README](../README.md)

| โฟลเดอร์ | เนื้อหา |
| --- | --- |
| `frontend/` | หน้าเว็บ HTML, CSS, JavaScript รูปภาพ ฟอนต์ และเซิร์ฟเวอร์หน้าบ้าน |
| `backend/src/` | API กฎธุรกิจ การยืนยันตัวตน และการเชื่อม MySQL |
| `backend/migrations/` | SQL สำหรับเปลี่ยนโครงสร้างฐานข้อมูล |
| `backend/scripts/` | เครื่องมือ migration, seed และ backup |
| `database/` | SQL โครงสร้างและข้อมูลสาธิตสำหรับติดตั้งใหม่ |
| `docs/reports/` | รายงานสรุป Portfolio ภาษาไทย ทั้ง PDF และ Markdown |
| `docs/postman/` | ชุดคำขอและค่าตั้งต้นสำหรับทดสอบ API |
| `docs/guides/` | คู่มือฉบับข้อความเดิม |
| `docs/` | คู่มือติดตั้ง API แผนผังหน้าเว็บ และผลทดสอบที่บันทึกไว้ |

## ตำแหน่งไฟล์ที่เปลี่ยน

เอกสาร PDF เดิมอาจแสดงชื่อโฟลเดอร์เก่าในเนื้อหา ตารางนี้แสดงตำแหน่งปัจจุบัน โดยลิงก์ใน PDF ได้ปรับให้ชี้ไปยังตำแหน่งใหม่แล้ว

| ตำแหน่งเดิม | ตำแหน่งปัจจุบัน |
| --- | --- |
| `docs/PORTFOLIO-REPORT.md` | `docs/reports/PORTFOLIO-REPORT.md` |
| `docs/portfolio-report-th.pdf` | `docs/reports/portfolio-report-th.pdf` |
| `readme.txt` | `docs/guides/legacy-installation.txt` |
| `sec2_gr8_database.sql` | `database/sec2_gr8_database.sql` |
| `sec2_gr8_fe_src/` | `frontend/` |
| `sec2_gr8_ws_src/` | `backend/` |

## รายการไฟล์ทั้งหมด

รายการนี้ไม่รวม node_modules ข้อมูลระหว่างใช้งาน และไฟล์ส่วนตัว

```text
backend/
  migrations/
    001_init.sql
    002_shop_workflow.sql
    003_categories.sql
    004_admin_profile.sql
  scripts/
    backup.js
    migrate.js
    seed-demo-catalog.js
  src/
    admin-routes.js
    approved-images.json
    categories.js
    category-routes.js
    commerce.js
    db.js
    demo-catalog.js
    frontend-paths.js
    product-images.js
    security.js
    seed.js
    server.js
    service-contract.js
    session-queue.js
    shop-routes.js
    view-data.js
  .env.example
  package-lock.json
  package.json
  README.md
database/
  sec2_gr8_database.sql
docs/
  guides/
    legacy-installation.txt
  postman/
    local.postman_environment.json
    sec2_gr8.postman_collection.json
  reports/
    portfolio-report-th.pdf
    PORTFOLIO-REPORT.md
  API.md
  HTML-PAGE-MAP.md
  html-pages.json
  INSTALLATION.md
  PUBLIC-API-TH.md
  REFERENCES.md
  service-catalog.json
  SERVICE-COVERAGE.md
  service-example-locations.json
  STRUCTURE.md
  team.json
frontend/
  public/
    admin/
      account-delete.html
      account-edit.html
      account-new.html
      accounts.html
      categories.html
      category-delete.html
      category-edit.html
      category-new.html
      customers.html
      index.html
      login.html
      messages.html
      order.html
      orders.html
      payments.html
      product-delete.html
      product-edit.html
      product-new.html
      products.html
      profile.html
      settings.html
    fonts/
      design-0.ttf
      design-1.ttf
      design-2.ttf
      design-3.ttf
      design-4.ttf
      design-5.ttf
      design-6.ttf
      design-7.ttf
      design-8.ttf
      design-9.ttf
      pdf-0.ttf
      pdf-1.ttf
    images/
      demo/
        ceramic-vase.webp
        floral-card.webp
        flower-tote.webp
        handmade-soap-set.webp
        heart-mug.webp
        mint-clock.webp
        pastel-bunny-plush.webp
        pink-notebook.webp
        rabbit-figurine.webp
        soap-flower-bouquet.webp
        vanilla-candle.webp
      figma/
        0927a.svg
        2a091.svg
        4378d.svg
        5a0ff.svg
        8059e.svg
        a3ef3.svg
        c6c4a.svg
        d7fe7.svg
      optimized/
        01563aa741fd80-480.webp
        01563aa741fd80-960.webp
        0969077687cdbe-480.webp
        0969077687cdbe-960.webp
        0fc8dddc99725a-480.webp
        0fc8dddc99725a-960.webp
        11cce377926026-480.webp
        11cce377926026-960.webp
        121da55f652ca5-480.webp
        121da55f652ca5-960.webp
        17bde4c9bf8d53-480.webp
        17bde4c9bf8d53-960.webp
        203a31331fdae0-480.webp
        203a31331fdae0-960.webp
        28eb0715693d31-480.webp
        28eb0715693d31-960.webp
        2a56db703af58b-480.webp
        2a56db703af58b-960.webp
        2cc11facd41cbd-480.webp
        2cc11facd41cbd-960.webp
        32678d91fbf2a3-480.webp
        32678d91fbf2a3-960.webp
        3f512fe076931a-480.webp
        3f512fe076931a-960.webp
        43990ab0f4358c-480.webp
        43990ab0f4358c-960.webp
        49794cc38e9a86-480.webp
        49794cc38e9a86-960.webp
        58fa6365f1bc9f-480.webp
        58fa6365f1bc9f-960.webp
        63e57110c01299-480.webp
        63e57110c01299-960.webp
        6a455974bda405-480.webp
        6a455974bda405-960.webp
        6c63e027c81e74-480.webp
        6c63e027c81e74-960.webp
        796754a5b1652a-480.webp
        796754a5b1652a-960.webp
        847023ffa869c3-480.webp
        847023ffa869c3-960.webp
        8e83a8577b6e4e-480.webp
        8e83a8577b6e4e-960.webp
        9c6e11ab8edbce-480.webp
        9c6e11ab8edbce-960.webp
        bb2d7a322e309e-480.webp
        bb2d7a322e309e-960.webp
        be624cd48fd2a6-480.webp
        be624cd48fd2a6-960.webp
        d06b93d7db6102-480.webp
        d06b93d7db6102-960.webp
        d32bad0f0c26e0-480.webp
        d32bad0f0c26e0-960.webp
        da283b804e7d75-480.webp
        da283b804e7d75-960.webp
        e19ef2d6e0b5fb-480.webp
        e19ef2d6e0b5fb-960.webp
        e4cf4d919349be-480.webp
        e4cf4d919349be-960.webp
        e81404212b1e95-480.webp
        e81404212b1e95-960.webp
        e9c883c77b6fb3-480.webp
        e9c883c77b6fb3-960.webp
        ea529e17465fec-480.webp
        ea529e17465fec-960.webp
        ef517c52d0eb52-480.webp
        ef517c52d0eb52-960.webp
        ef5e11b7f9c8d5-480.webp
        ef5e11b7f9c8d5-960.webp
        fc5c31881e197c-480.webp
        fc5c31881e197c-960.webp
        manifest.json
      team/
        member-1.webp
        member-2.webp
        member-3.webp
        member-4.webp
        member-5.webp
      admin-account-lock.svg
      admin-clock.svg
      admin-customers.svg
      admin-dashboard.svg
      admin-logout.svg
      admin-orders.svg
      admin-package.svg
      admin-products.svg
      admin-search.svg
      admin-wallet.svg
      asset-provenance.json
      product-placeholder.svg
      ui-edit.svg
      ui-trash.svg
      ui-upload.svg
    js/
      pages/
        about.js
        account-delete.js
        account-edit.js
        account-new.js
        account.js
        admin-accounts.js
        admin-categories.js
        admin-login.js
        admin-order.js
        admin-orders.js
        admin-products.js
        admin-profile.js
        cart.js
        category-delete.js
        category-edit.js
        category-new.js
        checkout.js
        contact.js
        customers.js
        dashboard.js
        favorites.js
        gift-budget.js
        help.js
        home.js
        login.js
        messages.js
        not-found.js
        order.js
        payments.js
        product-delete.js
        product-edit.js
        product-new.js
        product.js
        profile.js
        references.js
        register.js
        settings.js
        shop.js
        team.js
      shared/
        admin-forms.js
        auth.js
        dom.js
        image-assets.js
        image-credits.js
        order-list.js
        orders.js
        products.js
        profile.js
        public-service.js
      api.js
      app.js
      common.js
    404.html
    about.html
    account.html
    cart.html
    checkout.html
    contact.html
    favorites.html
    fonts.css
    gift-budget.html
    help.html
    index.html
    login.html
    modern.css
    order.html
    product.html
    profile.html
    references.html
    register.html
    shop.html
    team.html
  package.json
  page-paths.js
  README.md
  server.js
.gitignore
README.md
```
