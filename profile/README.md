<!-- logo -->
<p align="center">
  <img width='300' src="profile/readme/logo.png">
</p>
<!-- title -->
<h1 align="center" style="display:flex;justify-content:center;align-items:center;width:100%;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
    The Nonprofit Portal
    <img width="25" height="25" style="flex" src="profile/readme/title.svg" />
</h1>
<!-- powered by -->
<p align="center">
  <a aria-label="Vercel logo" href="https://vercel.com">
    <img src="https://img.shields.io/badge/POWERED%20BY%20Vercel-000.svg?style=for-the-badge&logo=Vercel&labelColor=000">
  </a>
  <a aria-label="Vercel logo" href="https://appwrite.io">
    <img src="https://img.shields.io/badge/AND%20appwrite-f02e65.svg?style=for-the-badge&labelColor=f02e65">
  </a>
</p>
<!-- brief description -->
<p align="center">
  <a href="#" target="_blank">
    <img alt="License" src="https://img.shields.io/github/license/The-Nonprofit-Portal/legal?style=flat-square&labelColor=343b41.svg"/>
  </a>
  <img alt="Stars" src="https://img.shields.io/github/stars/The-Nonprofit-Portal?style=flat-square&labelColor=343b41.svg"/>
  <img alt="Issues" src="https://img.shields.io/github/followers/The-Nonprofit-Portal?style=flat-square&labelColor=343b41.svg"/>  
  
  <p align="center">The Nonprofit Portal - a comprehensive platform dedicated to empowering nonprofit organizations! 👥</p>
</p>

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/overview.svg" />
  <span>Quick overview</span>
</h2>

<p align="center">Every day, countless nonprofit organizations work tirelessly to bring about positive change in our communities. But often, the lack of efficient tools for managing their activities slows down their momentum. We noticed this gap and took it as an opportunity to contribute.</p>

<p align="center">The Nonprofit Portal is a comprehensive web-based platform designed specifically for small to medium-sized nonprofits, their donors, and volunteers. Our mission? To streamline operations, foster transparency, and improve engagement within the nonprofit sector.</p>

<p align="center">
  <a href="https://thenonprofitportal.org">Website</a> •
  <a href="https://github.com/The-Nonprofit-Portal/legal/blob/main/LICENSE">License</a> •
  <a href="CONTRIBUTING.md">Contributing</a>
</p>

&nbsp;

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/architecture.svg" />
  <span>High Level Architecture</span>
</h2>

```mermaid
graph LR
    A[User] -- Actions --> B[Frontend: Next.js + TailwindCSS]
    B -- API Requests --> C[Backend: Appwrite]
    C -- Data Management --> D[Database]
    C -- User Management --> E[Account Service]
    C -- Realtime Updates --> F[Realtime Service]
    C -- Storage --> G[Storage Service]
```

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/features.svg" />
  <span>Features</span>
</h2>

<p align="center">Since this is an ongoing project, there are some features that are actively on development. Below are marked the ones that are currently supported. Stay tuned for upcoming ones!</p>

<h3 align="center">✨ ✨ ✨</h3>

- [ ] 🔐 **User Registration and Management**: Our platform supports role-based access, catering to admins, donors, and volunteers, each with customized dashboards to meet their specific needs.

- [ ] 💫 **Donation Tracking System**: Now donors can keep track of their contributions, and nonprofits can manage and acknowledge these donations efficiently.

- [ ] 🎗️ **Fundraising Campaign Management**: Launch, manage, and monitor fundraising campaigns, providing real-time updates to donors and volunteers.

- [ ] 📈 **Reporting and Analytics**: Gain insights into the organization's operations, donations, and campaigns with our easy-to-understand analytics dashboard.

- [ ] 🏦 **Payment Gateway Integration**: We've partnered with trusted services like Stripe and PayPal to facilitate secure financial transactions.

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/author.svg" />
  <span>Author</span>
</h2>

**Alain Iglesias**

- Website: https://aiherrera.com
- Blog: https://blog.aiherrera.com
- Twitter: [@\_aiherrera](https://twitter.com/_aiherrera)
- Github: [@aiherrera](https://github.com/aiherrera)
- LinkedIn: [@-aiherrera](https://linkedin.com/in/-aiherrera)

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/contribute.svg" />
  <span>Contribute</span>
</h2>

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/The-Nonprofit-Portal/thenonprofitportal.org/issues). You can also take a look at the [contributing guide](https://github.com/The-Nonprofit-Portal/thenonprofitportal.org/blob/master/CONTRIBUTING.md)

<h2 style="display:flex;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57">
  <img width="25" height="25" style="flex" src="profile/readme/support.svg" />
  <span>Support the project</span>
</h2>

<p style="margin-bottom:20px">If you consider this project worthy give it a ⭐️ and, why not, invite me a coffee 👇🤘🫶</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/aiherrera" target="_blank">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=aiherrera&button_colour=5F7FFF&font_colour=ffffff&font_family=Lato&outline_colour=000000&coffee_colour=FFDD00" />
  </a>
</p>

<h2 style="display:flex;justify-content:center;align-items:center;gap:10px;padding:10px 0;margin-bottom:20px;border-bottom:1px solid #4a4f57"></h2>
<p align="center">Copyright © 2023 Alain Iglesias | This project is MIT licensed</p>
