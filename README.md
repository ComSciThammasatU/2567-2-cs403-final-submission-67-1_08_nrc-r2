[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/w8H8oomW)
**<ins>Note</ins>: Students must update this `README.md` file to be an installation manual or a README file for their own CS403 projects.**

**รหัสโครงงาน:** 67-1_08_nrc-r2

**ชื่อโครงงาน (ไทย):** ฟาร์มลี่ เนเบอร์

**Project Title (Eng):** FARMLY NEIGHBOUR

**อาจารย์ที่ปรึกษาโครงงาน:** อ.ดร.นวฤกษ์ ชลารักษ์

**ผู้จัดทำโครงงาน:** (โปรดเขียนข้อมูลผู้จัดทำโครงงานตามฟอร์แมตดังแสดงในตัวอย่างด้านล่าง)
1. นายณธรรม ทองเอียง  6409610604  natum.ton@dome.tu.ac.th
2. นายศิวกร เกิดลาภี siwakorn.ker@dome.tu.ac.th
   
Manual / Instructions for your projects starts here !
# Directory Tree
<!-- TREEVIEW START -->
```bash
.env
.gitignore
|___extensions.json
|___settings.json
Instructions-for-Students.md
README.md
|___SessionWrapper.tsx
| | |___route.ts
| | | |___route.ts
| | |___route.ts
| | |___route.ts
| | |___route.ts
| | | |___route.ts
| | | |___route.ts
| | |___route.ts
| | |___route.ts
| | | |___route.ts
| | | |___route.ts
| | |___route.ts
| | |___route.ts
| | |___route.ts
| | | | | |___route.ts
| | | |___route.ts
| | | |___route.ts
| | | |___route.ts
| | | |___route.ts
| |___page.tsx
| |___layout.tsx
| | | |___page.tsx
| |___page.tsx
| | |___CommentForm.tsx
| | |___page.tsx
| |___layout.tsx
| | |___page.tsx
| |___page.tsx
| |___000049190039.jpg
| |___FarmlyNeighbor_logo_prototype_2.png
| |___logo.jpg
|___favicon.ico
|___globals.css
| |___layout.tsx
| |___page.tsx
|___layout.tsx
| |___page.tsx
|___page.tsx
| | |___page.tsx
| | |___page.tsx
| | |___page.tsx
| |___loading.tsx
| |___page.tsx
| |___page.tsx
| |___page.tsx
| | | |___page.tsx
| | |___page.tsx
| | | | |___page.tsx
| | |___page.tsx
| | |___CreateStorePage.tsx
| | |___DashboardPageClient.tsx
| | | |___OrdersDashboard.tsx
| | | |___ProductsDashboard.tsx
| | | |___page.tsx
| | | |___ChartPlaceHolder.tsx
| | | |___ChartRevenueByProducts.tsx
| | | |___Navbar.tsx
| | | |___OrderContext.tsx
| | | |___Sidebar.tsx
| | | |___StoreContext.tsx
| | |___layout.tsx
| | |___page.tsx
components.json
|___CartDrawer.tsx
|___OrderCard.tsx
|___ProductDetails.tsx
|___ReviewForm.tsx
|___ReviewList.tsx
|___addressList.tsx
|___bannerSection.tsx
|___cartList.tsx
|___miniMenu.tsx
|___miniNav.tsx
|___nav.tsx
|___productSection.tsx
| |___addProduct.tsx
| |___addtocartButton.tsx
| |___productCard.tsx
| |___productDetail.tsx
| |___benefitsSection.tsx
| |___storefrontpage.tsx
|___summarySection.tsx
| |___accordion.tsx
| |___alert-dialog.tsx
| |___alert.tsx
| |___aspect-ratio.tsx
| |___avatar.tsx
| |___badge.tsx
| |___breadcrumb.tsx
| |___button.tsx
| |___calendar.tsx
| |___card.tsx
| |___carousel.tsx
| |___chart.tsx
| |___checkbox.tsx
| |___collapsible.tsx
| |___command.tsx
| |___context-menu.tsx
| |___dialog.tsx
| |___drawer.tsx
| |___dropdown-menu.tsx
| |___form.tsx
| |___hover-card.tsx
| |___input-otp.tsx
| |___input.tsx
| |___label.tsx
| |___menubar.tsx
| |___navigation-menu.tsx
| |___pagination.tsx
| |___popover.tsx
| |___progress.tsx
| |___radio-group.tsx
| |___resizable.tsx
| |___scroll-area.tsx
| |___select.tsx
| |___separator.tsx
| |___sheet.tsx
| |___sidebar.tsx
| |___skeleton.tsx
| |___slider.tsx
| |___sonner.tsx
| |___switch.tsx
| |___table.tsx
| |___tabs.tsx
| |___textarea.tsx
| |___toggle-group.tsx
| |___toggle.tsx
| |___tooltip.tsx
|___CartContext.tsx
eslint.config.mjs
|___use-mobile.ts
|___files.ts
|___prisma.ts
|___supabase.ts
|___utils.ts
next.config.ts
output.txt
package-lock.json
package.json
postcss.config.mjs
| | |___migration.sql
| | |___migration.sql
| | |___migration.sql
| | |___migration.sql
| | |___migration.sql
| |___migration_lock.toml
|___schema.prisma
|___FarmlyNeighbor_logo_prototype_2.png
|___file copy.svg
|___file.svg
|___globe copy.svg
|___globe.svg
|___logo.jpg
|___next copy.svg
|___next.svg
|___vercel copy.svg
|___vercel.svg
|___window copy.svg
|___window.svg
|___.gitignore
|___config.toml
tailwind.config.js
treeview.sh
tsconfig.json
|___next-auth.d.ts

```

<!-- TREEVIEW END -->
# Prerequisite, Installation and CLI
**Prerequisite**
- NodeJS
  
**Installation**
1. โหลด NodeJS ในการใช้งาน library ที่ใช้ทำงานทั้งหมดในระบบ
https://nodejs.org/en/download
![image](https://github.com/user-attachments/assets/3725b71e-1949-457a-bdda-bd844d7836a4)

2. ติดตั้ง NodeJS ในเครี่อง
   
   ![image](https://github.com/user-attachments/assets/11dc68f4-6305-41d3-9e94-ca75bf7aab60)
   ![image](https://github.com/user-attachments/assets/21905fdb-ed99-4ce6-8db4-faf37b02e825)
   ![image](https://github.com/user-attachments/assets/9ed5be42-0738-4b39-b361-2f0dbd45834d)
   
   ![image](https://github.com/user-attachments/assets/1e56b129-3b6f-4796-b30b-767807f6ee44)
   ![image](https://github.com/user-attachments/assets/57602346-07de-4f36-bd75-59c6e4b024af)

3. ใช้คำสั่งในการโคลน repo ลงมา
   ```bash
   git clone https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_08_nrc-r2.git
   cd 2567-2-cs403-final-submission-67-1_08_nrc-r2
   ```
4. ใช้คำสั่งในการลง package ทุกตัว
   ```bash
   npm install
   npx prisma generate
   ```
5. ใช้คำสั่งในการเปิด localhost server
   ```bash
   npm run dev
   ```
6. เข้าเว็บด้วย
    ```
    http://localhost:3000
    ```
# Topic 3


