# Introduction 

[Bagisto](https://bagisto.com/en/) is a fantastic open-source eCommerce platform that allows businesses to create modern online stores easily. Bagisto offers a wide range of customizable features to meet the specific needs of any online business.

The platform is built on top of the reliable [Laravel](https://laravel.com/) framework, [Tailwind CSS](https://tailwindcss.com/) and [Vue.js](https://vuejs.org/), a user-friendly JavaScript framework. It provides businesses with a user-friendly interface and powerful tools to manage their online stores, handle inventory and orders, and create a smooth shopping experience for customers

### Navigating the Admin Panel

**Bagisto** reworks the admin menu to support **three levels**, so sections with their own sub-pages are reachable without leaving the sidebar. For example, **Settings >> Taxes** now opens **Tax Categories** and **Tax Rates** beneath it, and **Settings >> Data Transfer** opens **Imports**.

### Working with the Listing Grids

Most admin screens are listing grids — products, orders, customers, imports, and so on. They all share the same header, search box, **Filter** control, and pagination.

On a small screen, grids that define their own layout, such as **Catalog >> Products**, are shown as cards instead of a wide table. The column header is dropped there, because **Filter** and **Sort By** are reachable from the bar fixed to the foot of the screen. Grids that use the default layout keep the table and scroll sideways.

<ImagePopup src="/images/getting-started/mobileDatagrid.png" alt="Admin Listing Grid on Mobile" />

While a grid is loading, the placeholders now match the grid they stand in for on both desktop and mobile, so the layout no longer shifts once the rows arrive.

