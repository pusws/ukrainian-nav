EADME.md</path>
<content"># WebNav Hub / ВебНав Хаб

## 🌍 多语言支持 / Multi-language Support / Багатомовна підтримка

这个README提供中文、英语和乌克兰语版本。  
This README is available in Chinese, English, and Ukrainian.  
Цей README доступний китайською, англійською та українською мовами.

---

## 中文 / Chinese

### 立场声明

我们强烈谴责俄罗斯对乌克兰的侵略战争，支持乌克兰人民的正义斗争。我们呼吁世界各国团结起来，制止这场非正义的侵略，为乌克兰提供必要的援助和支持。  
为了表达对乌克兰的支持，我们的UI设计采用了乌克兰国旗的颜色主题（蓝色和金黄色），并将项目命名为"Ukrainian WebNav Hub"。

### 项目简介

**Ukrainian WebNav Hub** 是一个精心设计的网页导航平台，致力于为用户提供便捷、高效的网络资源访问体验。作为一个表达对乌克兰支持的项目，我们将导航功能与社会责任相结合。

#### 🎯 项目使命
- **简化网络生活**：将分散的网络资源集中整理，提供一站式导航服务
- **提升使用效率**：通过智能分类和快速搜索，帮助用户节省时间
- **表达立场支持**：通过设计元素和项目命名，表达对乌克兰人民的坚定支持

#### ✨ 核心价值
- **精心挑选的资源**：汇集全球优质网络服务，包括AI工具、社交媒体、实用工具等
- **用户友好的界面**：采用现代化设计，支持响应式布局，适配各种设备
- **无障碍访问**：纯静态部署，无需服务器，支持离线使用
- **持续更新**：定期维护和更新链接，确保资源的新鲜度和可用性

#### 🚀 适用场景
- **个人用户**：快速访问常用的网络服务和工具
- **开发者**：便捷查找开发相关的资源和文档
- **学生用户**：学术研究和学习资源的快速导航
- **内容创作者**：多平台发布和管理的统一入口

#### 📊 资源统计
- **6个主要分类**：AI搜索、社交媒体、实用工具、科技资讯、云存储、电子邮箱
- **50+优质链接**：涵盖国内外知名服务和工具
- **持续更新**：定期检查和更新链接有效性

### 项目结构

- `index.html` - 主页面HTML文件
- `style.css` - 样式文件
- `script.js` - JavaScript功能脚本

### 功能特点

- 响应式设计，适配移动端和桌面端
- 分类导航：AI搜索、社交媒体、实用工具、科技资讯、云存储、电子邮箱
- 平滑滚动导航
- 现代化的卡片式链接展示
- 悬停效果和视觉反馈
- 支持键盘导航

### 链接分类

#### AI搜索
包含各种AI工具和聊天机器人链接

#### 社交媒体
Facebook、Twitter、Instagram等社交平台

#### 实用工具
翻译工具、网速测试、域名工具等

#### 科技资讯
TechCrunch、Wired、The Verge等科技新闻网站

#### 云存储
Google Drive、Dropbox、OneDrive等

#### 电子邮箱
Gmail、Outlook、ProtonMail等

### 使用方法

1. 克隆项目到本地
2. 打开 `index.html` 文件即可在浏览器中查看
3. 点击导航栏切换不同分类
4. 点击链接卡片访问相应网站

### 技术栈

- HTML5
- CSS3 (使用CSS变量和Flexbox/Grid布局)
- JavaScript (ES6+)
- FontAwesome图标库

### 浏览器兼容性

支持所有现代浏览器，包括Chrome、Firefox、Safari、Edge。

### 部署说明

#### 本地部署
1. 克隆项目到本地
2. 直接打开 `index.html` 文件即可使用
3. 无需服务器，支持静态文件部署

#### 在线部署
可部署到任何支持静态网站的平台：
- GitHub Pages
- Vercel
- Netlify
- 腾讯云静态网站托管
- 阿里云OSS静态网站

### 开发说明

#### 文件结构
```
WebNav Hub/
├── index.html      # 主页面
├── style.css       # 样式文件
├── script.js       # JavaScript功能
└── README.md       # 项目说明
```

#### 自定义链接和分类

本项目支持灵活的自定义，您可以根据需要添加、删除或修改链接和分类。

##### 添加新链接
如需在现有分类中添加新链接，请在相应的 `<section class="link-grid">` 中添加新的 `<div class="link-card">` 元素：

```html
<div class="link-card">
  <a href="https://example.com" target="_blank"></a>
  <i class="fa-solid fa-link"></i>
  <h3>链接名称</h3>
</div>
```

##### 删除现有链接
要删除链接，只需删除相应的 `<div class="link-card">` 元素即可。

##### 添加新分类
要添加新分类，请按照以下步骤操作：

1. **添加导航菜单项**：在 `<nav>` 的 `<ul>` 中添加新的链接
```html
<li><a href="#new-category">新分类</a></li>
```

2. **添加分类内容区域**：在 `main` 元素中添加新的分类区域
```html
<h2 class="category-title" id="new-category">新分类</h2>
<section class="link-grid">
  <!-- 在此处添加链接卡片 -->
</section>
```

##### 删除现有分类
要删除整个分类：
1. 删除导航菜单中的对应链接
2. 删除 `main` 中的整个分类区域（包括标题和链接网格）

##### 图标选择
项目使用 FontAwesome 图标库，您可以：
- 在 [FontAwesome 官网](https://fontawesome.com/icons) 选择合适的图标
- 使用 `<i class="fa-solid fa-icon-name"></i>` 格式
- 常用图标类：`fa-brands`（品牌）、`fa-solid`（实心）、`fa-regular`（空心）

##### 注意事项
- 确保链接 URL 正确且可访问
- 为移动端优化考虑，链接标题应简洁明了
- 定期检查链接有效性，及时更新失效链接

### 贡献指南

欢迎提交 Issue 和 Pull Request 来改进这个项目！

### 更新日志

#### v1.0.0 (2025)
- 初始版本发布
- 包含AI搜索、社交媒体、实用工具、科技资讯、云存储、电子邮箱等分类
- 支持响应式设计

### 许可证

保留所有权利 © 2025 Ukrainian WebNav Hub

---

## English

### Position Statement

We strongly condemn Russia's invasion of Ukraine and support the Ukrainian people's just struggle. We call on all countries around the world to unite and stop this unjust aggression, and to provide Ukraine with the necessary assistance and support.  
To express our support for Ukraine, our UI design incorporates the colors of the Ukrainian flag (blue and gold), and we have named the project "Ukrainian WebNav Hub".

### Project Description

**Ukrainian WebNav Hub** is a meticulously designed web navigation platform dedicated to providing users with convenient and efficient access to online resources. As a project expressing support for Ukraine, we combine navigation functionality with social responsibility.

#### 🎯 Project Mission
- **Simplify Online Life**: Centralize scattered online resources and provide one-stop navigation services
- **Improve Efficiency**: Help users save time through intelligent categorization and quick access
- **Express Support**: Demonstrate firm support for the Ukrainian people through design elements and project naming

#### ✨ Core Value
- **Carefully Selected Resources**: A collection of global high-quality online services, including AI tools, social media, utilities, etc.
- **User-Friendly Interface**: Modern design with responsive layout, compatible with various devices
- **Barrier-Free Access**: Pure static deployment, no server required, supports offline use
- **Continuous Updates**: Regular maintenance and updates to links to ensure freshness and availability

#### 🚀 Use Cases
- **Individual Users**: Quick access to commonly used online services and tools
- **Developers**: Convenient access to development-related resources and documentation
- **Students**: Quick navigation for academic research and learning resources
- **Content Creators**: Unified entry point for multi-platform publishing and management

#### 📊 Resource Statistics
- **6 Main Categories**: AI Search, Social Media, Tools, Tech News, Cloud Storage, Email
- **50+ Quality Links**: Covering well-known domestic and international services and tools
- **Continuous Updates**: Regular checking and updating of link validity

### Project Structure

- `index.html` - Main HTML page
- `style.css` - Stylesheet
- `script.js` - JavaScript functionality

### Features

- Responsive design, compatible with mobile and desktop
- Category navigation: AI Search, Social Media, Tools, Tech News, Cloud Storage, Email
- Smooth scroll navigation
- Modern card-style link display
- Hover effects and visual feedback
- Keyboard navigation support

### Link Categories

#### AI Search
Contains links to various AI tools and chatbots

#### Social Media
Facebook, Twitter, Instagram and other social platforms

#### Tools
Translation tools, speed tests, domain tools, etc.

#### Tech News
TechCrunch, Wired, The Verge and other technology news websites

#### Cloud Storage
Google Drive, Dropbox, OneDrive, etc.

#### Email
Gmail, Outlook, ProtonMail, etc.

### Usage

1. Clone the project locally
2. Open the `index.html` file to view in browser
3. Click navigation bar to switch categories
4. Click link cards to access respective websites

### Tech Stack

- HTML5
- CSS3 (using CSS variables and Flexbox/Grid layouts)
- JavaScript (ES6+)
- FontAwesome icon library

### Browser Compatibility

Supports all modern browsers, including Chrome, Firefox, Safari, Edge.

### Deployment Instructions

#### Local Deployment
1. Clone the project locally
2. Open the `index.html` file directly
3. No server required, supports static file deployment

#### Online Deployment
Can be deployed to any platform that supports static websites:
- GitHub Pages
- Vercel
- Netlify
- Tencent Cloud Static Website Hosting
- Alibaba Cloud OSS Static Website

### Development Documentation

#### File Structure
```
WebNav Hub/
├── index.html      # Main page
├── style.css       # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # Project documentation
```

#### Customizing Links and Categories

This project supports flexible customization, allowing you to add, remove, or modify links and categories as needed.

##### Adding New Links
To add new links within existing categories, add new `<div class="link-card">` elements in the corresponding `<section class="link-grid">`:

```html
<div class="link-card">
  <a href="https://example.com" target="_blank"></a>
  <i class="fa-solid fa-link"></i>
  <h3>Link Name</h3>
</div>
```

##### Removing Existing Links
To remove links, simply delete the corresponding `<div class="link-card">` element.

##### Adding New Categories
To add new categories, follow these steps:

1. **Add Navigation Menu Item**: Add a new link in the `<ul>` within `<nav>`
```html
<li><a href="#new-category">New Category</a></li>
```

2. **Add Category Content Area**: Add a new category section within the `main` element
```html
<h2 class="category-title" id="new-category">New Category</h2>
<section class="link-grid">
  <!-- Add link cards here -->
</section>
```

##### Removing Existing Categories
To remove an entire category:
1. Delete the corresponding link from the navigation menu
2. Delete the entire category section from `main` (including title and link grid)

##### Icon Selection
The project uses the FontAwesome icon library. You can:
- Choose appropriate icons from the [FontAwesome website](https://fontawesome.com/icons)
- Use the `<i class="fa-solid fa-icon-name"></i>` format
- Common icon classes: `fa-brands` (brands), `fa-solid` (solid), `fa-regular` (regular)

##### Important Notes
- Ensure link URLs are correct and accessible
- Keep link titles concise for mobile optimization
- Regularly check link validity and update broken links

### Contributing Guidelines

Welcome to submit Issues and Pull Requests to improve this project!

### Changelog

#### v1.0.0 (2025)
- Initial release
- Includes AI search, social media, tools, tech news, cloud storage, email categories
- Supports responsive design

### License

All rights reserved © 2025 Ukrainian WebNav Hub

---

## Українська / Ukrainian

### Заява про позицію

Ми рішуче засуджуємо вторгнення Росії в Україну та підтримуємо справедливу боротьбу українського народу. Ми закликаємо всі країни світу об'єднатися, щоб зупинити цю несправедливу агресію та надати Україні необхідну допомогу та підтримку.  
Щоб висловити нашу підтримку Україні, наш дизайн інтерфейсу використовує кольори українського прапора (синій та золотий), і ми назвали проект "Ukrainian WebNav Hub".

### Опис проекту

**Ukrainian WebNav Hub** — це ретельно розроблена платформа веб-навігації, присвячена наданню користувачам зручного та ефективного доступу до онлайн-ресурсів. Як проект, що висловлює підтримку Україні, ми поєднуємо функціональність навігації із соціальною відповідальністю.

#### 🎯 Місія проекту
- **Спростити онлайн-життя**: Централізувати розпорошені онлайн-ресурси та надавати комплексні навігаційні послуги
- **Підвищити ефективність**: Допомогти користувачам заощадити час завдяки інтелектуальній категоризації та швидкому доступу
- **Висловити підтримку**: Продемонструвати тверду підтримку українського народу через елементи дизайну та назву проекту

#### ✨ Основна цінність
- **Ретельно відібрані ресурси**: Збірка глобальних високоякісних онлайн-сервісів, включаючи інструменти ШІ, соціальні мережі, утиліти тощо
- **Дружній інтерфейс**: Сучасний дизайн із адаптивним макетом, сумісний із різними пристроями
- **Доступ без бар'єрів**: Чистий статичний розгортання, сервер не потрібен, підтримує офлайн-використання
- **Неперервні оновлення**: Регулярне обслуговування та оновлення посилань для забезпечення свіжості та доступності

#### 🚀 Сфери застосування
- **Особисті користувачі**: Швидкий доступ до часто використовуваних онлайн-сервісів та інструментів
- **Розробники**: Зручний доступ до ресурсів та документації, пов'язаних із розробкою
- **Студенти**: Швидка навігація для академічних досліджень та навчальних ресурсів
- **Творці контенту**: Єдиний пункт входу для публікації та управління на кількох платформах

#### 📊 Статистика ресурсів
- **6 основних категорій**: AI Пошук, Соціальні мережі, Інструменти, Технічні новини, Хмарне сховище, Електронна пошта
- **50+ якісних посилань**: Охоплює відомі вітчизняні та міжнародні сервіси та інструменти
- **Неперервні оновлення**: Регулярна перевірка та оновлення дійсності посилань

### Структура проекту

- `index.html` - Головна HTML-сторінка
- `style.css` - Стильова таблиця
- `script.js` - Функціональність JavaScript

### Особливості

- Адаптивний дизайн, сумісний із мобільними та настільними пристроями
- Навігація за категоріями: AI Пошук, Соціальні мережі, Інструменти, Технічні новини, Хмарне сховище, Електронна пошта
- Плавна навігація із прокруткою
- Сучасний відображення посилань у стилі карток
- Ефекти наведення та візуальний зворотний зв'язок
- Підтримка навігації клавіатурою

### Категорії посилань

#### AI Пошук
Містить посилання на різні інструменти ШІ та чат-боти

#### Соціальні мережі
Facebook, Twitter, Instagram та інші соціальні платформи

#### Інструменти
Інструменти перекладу, тести швидкості, інструменти доменів тощо

#### Технічні новини
TechCrunch, Wired, The Verge та інші сайти технічних новин

#### Хмарне сховище
Google Drive, Dropbox, OneDrive тощо

#### Електронна пошта
Gmail, Outlook, ProtonMail тощо

### Використання

1. Клонувати проект локально
2. Відкрити файл `index.html` для перегляду в браузері
3. Натиснути панель навігації для переключення категорій
4. Натиснути картки посилань для доступу до відповідних веб-сайтів

### Технологічний стек

- HTML5
- CSS3 (використання CSS-змінних та Flexbox/Grid макетів)
- JavaScript (ES6+)
- Бібліотека іконок FontAwesome

### Сумісність із браузерами

Підтримує всі сучасні браузери, включаючи Chrome, Firefox, Safari, Edge.

### Інструкції з розгортання

#### Локальне розгортання
1. Клонувати проект локально
2. Відкрити файл `index.html` безпосередньо
3. Сервер не потрібен, підтримує розгортання статичних файлів

#### Онлайн-розгортання
Можна розгорнути на будь-якій платформі, що підтримує статичні веб-сайти：
- GitHub Pages
- Vercel
- Netlify
- Tencent Cloud Static Website Hosting
- Alibaba Cloud OSS Static Website

### Документація для розробників

#### Структура файлів
```
WebNav Hub/
├── index.html      # Головна сторінка
├── style.css       # Стильова таблиця
├── script.js       # Функціональність JavaScript
└── README.md       # Документація проекту
```

#### Налаштування посилань та категорій

Цей проект підтримує гнучке налаштування, що дозволяє додавати, видаляти або змінювати посилання та категорії за потребою.

##### Додавання нових посилань
Щоб додати нові посилання в існуючих категоріях, додайте нові елементи `<div class="link-card">` у відповідному `<section class="link-grid">`:

```html
<div class="link-card">
  <a href="https://example.com" target="_blank"></a>
  <i class="fa-solid fa-link"></i>
  <h3>Назва посилання</h3>
</div>
```

##### Видалення існуючих посилань
Щоб видалити посилання, просто видаліть відповідний елемент `<div class="link-card">`.

##### Додавання нових категорій
Щоб додати нові категорії, виконайте наступні кроки:

1. **Додати пункт меню навігації**: Додайте нове посилання в `<ul>` в межах `<nav>`
```html
<li><a href="#new-category">Нова категорія</a></li>
```

2. **Додати область вмісту категорії**: Додайте новий розділ категорії в елементі `main`
```html
<h2 class="category-title" id="new-category">Нова категорія</h2>
<section class="link-grid">
  <!-- Додайте картки посилань тут -->
</section>
```

##### Видалення існуючих категорій
Щоб видалити всю категорію:
1. Видаліть відповідне посилання з меню навігації
2. Видаліть весь розділ категорії з `main` (включаючи заголовок і сітку посилань)

##### Вибір іконок
Проект використовує бібліотеку іконок FontAwesome. Ви можете:
- Обирати відповідні іконки з [сайту FontAwesome](https://fontawesome.com/icons)
- Використовувати формат `<i class="fa-solid fa-icon-name"></i>`
- Поширені класи іконок: `fa-brands` (бренди), `fa-solid` (суцільні), `fa-regular` (звичайні)

##### Важливі зауваження
- Переконайтеся, що URL посилань правильні та доступні
- Зберігайте назви посилань стислими для мобільної оптимізації
- Регулярно перевіряйте дійсність посилань та оновлюйте непрацюючі посилання

### Керівні принципи внеску

Ласкаво просимо надсилати Issues та Pull Requests для покращення цього проекту！

### Журнал змін

#### v1.0.0 (2025)
- Початковий реліз
- Включає категорії AI пошуку, соціальних мереж, інструментів, технічних новин, хмарного сховища, електронної пошти
- Підтримує адаптивний дизайн

### Ліцензія

Усі права захищені © 2025 Ukrainian WebNav Hub