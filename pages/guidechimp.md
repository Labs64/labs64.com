---
layout: page
title: "Deliver the Perfect Product Experience"
description: "Create interactive guided product tours in minutes with GuideChimp - the most non-technical friendly, lightweight and extendable library."
permalink: "/guidechimp/"
tags:
- guide
- guided tour
- product tour
- user flow
- user experience
- user training
- user manual
- onboarding
- feature adoption
- employee training
- tooltips
- beacon
- hint
- hotspot
- walkthrough
- engagement
---

<div class="row NL_banner">
    <div class="col-md-8 col-md-offset-2 NL_about">
        <h1>{{ page.title }}</h1>
        <span>Create interactive guided product tours in minutes with GuideChimp<br/>The most non-technical friendly, lightweight and extendable library.</span>
        <div class="row">
            <div id="guidechimp-demo" class="col-md-4 col-md-offset-2">
                <a href="#" id="guidechimp-demo"
                   class="NL_button button_main NL_light_btn" role="button"><i class="fa fa-eye"></i>Demo</a>
            </div>
            <div id="documentation" class="col-md-4">
                <a href="https://github.com/Labs64/GuideChimp/wiki"
                   class="NL_button button_main NL_light_btn" role="button"><i class="fa fa-book"></i>Documentation</a>
            </div>
        </div>
    </div>
</div> 

<div class="row">
    <div id="cbp-so-scroller" class="cbp-so-scroller NL_intro">
        <section class="cbp-so-section">
            <figure class="cbp-so-side cbp-so-side-left">
                <img src="{{ '/img/guidechimp-logo-notext-transparent.png' | prepend: site.baseurl | prepend: site.url }}" alt="Areas of expertise" title="Areas of expertise">
            </figure>
            <article class="cbp-so-side cbp-so-side-right">
                <h2>Framework Ready</h2>
                <span>GuideChimp is ready to drop into your application using React, Vue.js, Angular, ES Modules, or plain JavaScript and HTML.</span>
            </article>
        </section>

        <section class="cbp-so-section">
            <article id="maximize-revenue" class="cbp-so-side cbp-so-side-left">
                <h2>Highly Customizable</h2>
                <span>GuideChimp styles are kept minimal, allowing you to easily customize the look and feel, but still give you enough to drop in and be ready to go quickly.</span>
            </article>
            <figure class="cbp-so-side cbp-so-side-right">
                <img src="{{ '/img/guidechimp-logo-notext-transparent.png' | prepend: site.baseurl | prepend: site.url }}" alt="Consulting" title="Consulting">
            </figure>
        </section>

        <section class="cbp-so-section">
            <figure class="cbp-so-side cbp-so-side-left">
                <img src="{{ '/img/guidechimp-logo-notext-transparent.png' | prepend: site.baseurl | prepend: site.url }}" alt="Outsourcing" title="Outsourcing">
            </figure>
            <article id="reduce-ecommerce-complexity" class="cbp-so-side cbp-so-side-right">
                <h2>Extendable</h2>
                <span>GuideChimp is easily extendable using out-of-the-box and third-party plugins.</span>
            </article>
        </section>

        <section class="cbp-so-section">
            <article id="maximize-revenue" class="cbp-so-side cbp-so-side-left">
                <h2>Dual-Licensed</h2>
                <span>Open Source (European Union Public License v1.2) and Commercial (including great support, maintenance and customized implementation)</span>
            </article>
            <figure class="cbp-so-side cbp-so-side-right">
                <img src="{{ '/img/guidechimp-logo-notext-transparent.png' | prepend: site.baseurl | prepend: site.url }}" alt="Consulting" title="Consulting">
            </figure>
        </section>

    </div>
</div>

<div class="row">
    <div class="col-md-12 NL_form_light NL_block">
        <div class="col-md-8 col-md-offset-2 NL_form_light_text">
            <h2>Ready to start?</h2>
            <span>Start reading GuideChimp documentation.</span>

            <form action="https://github.com/Labs64/GuideChimp/wiki" method="GET"
                  name="Wiki" id="wiki"
                  novalidate>
                <button type="submit" class="NL_button button_main NL_dark_btn NL_wide_btn"><i class="fa fa-github"></i>Star on GitHub</button>
            </form>
        </div>
    </div>
</div>

<div class="row NL_block">
    <h2 class="col-md-12">GuideChimp Licensing</h2>

    <p class="col-md-8 col-md-offset-2" style="text-align:center;">GuideChimp is made available under the <i>European Union Public License, version 1.2</i> or <i>Commercial License</i>. The Commercial License requires the payment of a fee for each designated commercial application.
    If you choose not to pay a fee and use the European Union Public License, version 1.2, you are required to release the source code of any program that you distribute that uses GuideChimp.
    If you choose to pay for a Commercial License, you are not required to disclose your source code.</p>
</div>

<div class="row NL_block NL_pricing">
    {% include pricing-table-guidechimp.html %}
</div>

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/guidechimp.min.css"/>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/guidechimp.min.js"></script>
<script>
    var tourGuideChimp = [
        {
            element: '[data-id="id-9"]',
            title: 'Node-Locked',
            description: 'Software is licensed for use only on one or more <i>named computer systems</i>. Usually, CPU serial number verification is used to enforce this type of license.',
            buttons: [
                {
                    title: 'Learn More',
                    class: 'NL_button button_main NL_dark_btn NL_wide_btn',
                    onClick: function () {
                        window.location.href = 'https://netlicensing.io/wiki/node-locked';
                    }
                }
            ]
        }
    ];

    var guideChimp = new GuideChimp(tourGuideChimp);
    document.getElementById('guidechimp-demo').onclick = function() {
        guideChimp.start();
    };
</script>
<style>
    .gc-tooltip {
        max-width: 450px;
    }
</style>
