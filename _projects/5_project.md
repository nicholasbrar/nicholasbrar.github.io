---
layout: page
title: DealerShock Mobile App
description: React Native (Expo) app for dealers—VIN scanner, WebView dashboard, push notifications.
img: assets/img/projects/dealershock_mobile/IMG_6759.PNG
importance: 3
category: work
images:
  slider: true
---

**DealerDashboardApp** is a React Native mobile app I built with Expo for Dealer Shock, giving dealers native iOS and Android access to their existing web dashboard. Rather than rebuilding the dashboard from scratch, I wrapped it in a WebView and focused my energy on the mobile-specific features that actually made the app worth having.

I built a **VIN scanner** screen that uses the device camera to read barcodes and deep-links into the dashboard's inventory-add flow with the scanned VIN pre-loaded, saving dealers a lot of manual entry. The app handles **authentication** with persistent credentials and **role-based routing**, so users land where they need to without any friction.

On the **notifications** side, I wired up Expo push tokens to Supabase, registering them per user and dealership so the app can deliver targeted push alerts. It ships as a polished native app on both iOS and Android, complete with EAS updates, splash screen, and notification icons.

<div class="row justify-content-sm-center mt-4">
    <div class="col-sm-12 col-md-8 col-lg-6">
        <swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" rewind="true">
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/dealershock_mobile/IMG_6759.PNG" title="Dealer Shock app" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/dealershock_mobile/IMG_6760.PNG" title="Dealer Shock app" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/dealershock_mobile/IMG_6761.PNG" title="Dealer Shock app" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/dealershock_mobile/IMG_6763.PNG" title="Dealer Shock app" class="img-fluid rounded z-depth-1" %}</swiper-slide>
            <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/projects/dealershock_mobile/IMG_6764.PNG" title="Add to Inventory with VIN scan" class="img-fluid rounded z-depth-1" %}</swiper-slide>
        </swiper-container>
        <div class="caption">
            Dealer Shock mobile app—dashboard access, navigation, and VIN scanner flow for adding inventory.
        </div>
    </div>
</div>
