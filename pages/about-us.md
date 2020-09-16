---
layout: page
title: "About Us"
description: "Labs64 is an independent IT service provider based out of Germany with people around the world."
permalink: "/about-us/"
tags:
- contact
---

<div class="row NL_banner">
    <div class="col-md-8 col-md-offset-2 NL_about">
        <h1>{{ page.title }}</h1>
        <span>{{ page.description }}</span>
    </div>
</div>

<div class="row">
    <div id="cbp-so-scroller" class="cbp-so-scroller NL_intro">
        <section class="cbp-so-section">
            <figure class="cbp-so-side cbp-so-side-left">
                <img src="{{ '/img/labs64-office-03_hl.jpg' | prepend: site.baseurl | prepend: site.url }}" alt="Welcome to Labs64" title="Welcome to Labs64">
            </figure>
            <article class="cbp-so-side cbp-so-side-right">
                <h2>Welcome to Labs64</h2>
                <span>Labs64 is an independent IT service provider based out of Germany with people around the world. We design, develop and implement a broad range of IT solutions based on our customer’s individual requirements. Labs64 focusses on finance, telecommunications, automotive, and automation technology industries as well as on hardware, software and online solutions. We provide our customers with expert advice and support, all the way from the initial concept to the implementation. With more than fifty years of combined IT experience, we understand business processes and design solutions to ensure our customer’s ongoing success. Our background is creative, we love open source, we believe that work is about way more than just making money, and we’re totally committed to making products that are awesome!
                Our client base includes small and medium-sized companies as well as global enterprises, such as BMW, Siemens Enterprise Communications, MSI Solutions, WIP Immobilien, Wirecard, Zurich Instruments.</span>
            </article>
        </section>
    </div>
</div>

<div class="row">
    <div class="col-md-12 NL_form_light NL_block">
        <div class="col-md-8 col-md-offset-2 NL_form_light_text">
            <h2>Learn more about Labs64</h2>
            <span>Get to know more about the people behind Labs64.</span>

            <form action="/our-team/" method="GET"
                  name="Management" id="management"
                  novalidate>
                <button type="submit" class="NL_button button_main NL_dark_btn NL_wide_btn">
                    <i class="fa fa-users "></i>Management
                </button>
            </form>
        </div>
    </div>
</div>
