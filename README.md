# Food Delivery Backend with Order Management

## Overview

The **Food Delivery Backend** provides APIs to manage restaurant menus, handle orders, and simulate order status updates. This system serves as the backbone of a food delivery service where users can add menu items, place orders, track order statuses, and simulate the delivery process.

## Features

- **Add Menu Item**: Add new menu items with details like name, price, and category.
- **Get Menu**: Retrieve a list of all menu items.
- **Place Order**: Create an order by selecting items from the menu.
- **Get Order**: Fetch details of a specific order by its ID.
- **Update Order Status**: Automate order status updates through a cron job. The status changes from `Preparing` → `Out for Delivery` → `Delivered`.

## Requirements

- **Node.js** (v14+ recommended)
- **npm** (v6+ recommended)

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/food-delivery-backend.git
