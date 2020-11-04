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
image:
  url: /img/guidechimp/guidechimp-stage-03.png
---

<div class="row NL_banner">
    <div class="col-md-8 col-md-offset-2 NL_about">
        <h1>{{ page.title }}</h1>
        <span>Create interactive guided product tours in minutes with GuideChimp<br/>The most non-technical friendly, lightweight and extendable library.</span>
        <div class="row">
            <div class="col-md-4 col-md-offset-2">
                <a href="#" id="guidechimp-demo"
                   class="NL_button button_main NL_light_btn" role="button"><i class="fa fa-eye"></i>Demo Tour</a>
            </div>
            <div class="col-md-4">
                <a href="https://github.com/Labs64/GuideChimp/wiki" id="guidechimp-documentation"
                   class="NL_button button_main NL_light_btn" role="button"><i class="fa fa-book"></i>Documentation</a>
            </div>
        </div>
    </div>
</div>

<div class="row">
    <div id="cbp-so-scroller" class="cbp-so-scroller NL_intro">
        <section class="cbp-so-section">
            <figure class="cbp-so-side cbp-so-side-left">
                <img src="{{ '/img/guidechimp/guidechimp-01-framework.png' | prepend: site.baseurl | prepend: site.url }}" alt="Framework Ready" title="Framework Ready">
            </figure>
            <article id="framework" class="cbp-so-side cbp-so-side-right">
                <h2>Framework Ready</h2>
                <span>GuideChimp can be seamlessly integrated with any web app and ready to drop into your application using React, Vue.js, Angular, ES Modules, or plain JavaScript and HTML.</span>
            </article>
        </section>

        <section class="cbp-so-section">
            <article id="customizable" class="cbp-so-side cbp-so-side-left">
                <h2>Highly Customizable</h2>
                <span>GuideChimp works well with tools you already use and can be easily customized through SCSS and clean CSS to look like an integral part of your product.</span>
            </article>
            <figure class="cbp-so-side cbp-so-side-right">
                <img src="{{ '/img/guidechimp/guidechimp-02b-customizable.png' | prepend: site.baseurl | prepend: site.url }}" alt="Customizable" title="Customizable">
            </figure>
        </section>

        <section class="cbp-so-section">
            <figure class="cbp-so-side cbp-so-side-left">
                <img src="{{ '/img/guidechimp/guidechimp-03-extendable.png' | prepend: site.baseurl | prepend: site.url }}" alt="Extendable" title="Extendable">
            </figure>
            <article id="extendable" class="cbp-so-side cbp-so-side-right">
                <h2>Extendable</h2>
                <span>GuideChimp is extendable using out-of-the-box and third-party plugins, which enhance functionality with usability, feedback, analytics, etc. tools.</span>
            </article>
        </section>

        <section class="cbp-so-section">
            <article id="developers" class="cbp-so-side cbp-so-side-left">
                <h2>Developers Friendly</h2>
                <span>GuideChimp is well documented and the open-source library is easy to integrate and have a very short learning curve.</span>
            </article>
            <figure class="cbp-so-side cbp-so-side-right">
                <img src="{{ '/img/guidechimp/guidechimp-04-developer.png' | prepend: site.baseurl | prepend: site.url }}" alt="Developers Friendly" title="Developers Friendly">
            </figure>
        </section>

    </div>
</div>

<div class="row">
    <div class="col-md-12 NL_form_light NL_block">
        <div class="col-md-8 col-md-offset-2 NL_form_light_text">
            <h2>Powerful, flexible features</h2>
            <span>Engage better with your Users, Improve User Experience and Increase Feature and Product Adoption.</span>

            <form action="https://github.com/Labs64/GuideChimp/wiki/Examples" method="GET"
                  name="Examples" id="Examples"
                  novalidate>
                <button type="submit" id="guidechimp-examples" class="NL_button button_main NL_dark_btn NL_wide_btn"><i class="fa fa-eye"></i>Examples</button>
            </form>
        </div>
    </div>
</div>

<div class="row">
    <div style="padding:40px;">
        {% for feature in site.data.guidechimp %}
        <div class="col-md-3 NL_feature" id="feature-{{ feature.name | slugify }}">
            <figure class="hover_effect">
                <figcaption>
                <img src="{{ feature.icon | prepend: site.baseurl | prepend: site.url }}" alt="{{ feature.name }}"/>
                <h3>
                {{ feature.name }}
                </h3>

                <p>{{ feature.description }}</p>
                </figcaption>
            </figure>
        </div>
        {% endfor %}
    </div>
</div>

<div class="row">
    <div class="col-md-12 NL_form_light NL_block">
        <div class="col-md-8 col-md-offset-2 NL_form_light_text">
            <h2>GuideChimp loved by many</h2>
            <span>The world's smartest companies using GuideChimp open-source library to boost their user experience.</span>

            <form action="https://github.com/Labs64/GuideChimp" method="GET"
                  name="GitHub" id="github"
                  novalidate>
                <button type="submit" id="guidechimp-github" class="NL_button button_main NL_dark_btn NL_wide_btn"><i class="fa fa-github"></i>Star on GitHub</button>
            </form>
        </div>
    </div>
</div>

<div class="row NL_block">
    <h2 id="guidechimp-licensing" class="col-md-12">GuideChimp Licensing</h2>

    <p class="col-md-8 col-md-offset-2" style="text-align:center;">GuideChimp is made available under the <i>European Union Public License, version 1.2</i> or <i>Commercial License</i>.
    <br>The Commercial License requires the payment of a fee for each designated commercial application.
    <br>If you choose not to pay a fee and use the <i>European Union Public License, version 1.2</i>, you are required to release the source code of any program that you distribute that uses GuideChimp.
    <br>If you choose to pay for a <i>Commercial License</i>, you are not required to disclose your source code.
    </p>
</div>

<div class="row NL_block NL_pricing">
    {% include pricing-table-guidechimp.html %}
</div>

<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/guidechimp.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/plugins/beacons.min.js"></script>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/guidechimp.min.css"/>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/guidechimp@2/dist/plugins/beacons.min.css">

<script>
    GuideChimp.extend(guideChimpPluginBeacons);
    var tourGuideChimp = [
        {
            element: '#guidechimp-demo',
            title: 'GuideChimp Demo',
            description: 'See GuideChimp in action, right here & now, on your screen.'
        },
        {
            element: '#guidechimp-documentation',
            title: 'GuideChimp Documentation',
            description: 'In GuideChimp Wiki, you will see how to install and configure GuideChimp for your needs, as well as lots of useful examples and tips.',
            buttons: [
                {
                    title: 'Open Wiki',
                    class: 'NL_button button_main NL_dark_btn NL_wide_btn',
                    onClick: function () {
                        window.open('https://github.com/Labs64/GuideChimp/wiki', '_blank');
                    }
                }
            ]
        },
        {
            element: '#guidechimp-examples',
            title: 'GuideChimp Examples',
            description: 'See all GuideChimp examples in action at CodePen and live Websites.',
            buttons: [
                {
                    title: 'See Examples',
                    class: 'NL_button button_main NL_dark_btn NL_wide_btn',
                    onClick: function () {
                        window.open('https://github.com/Labs64/GuideChimp/wiki/Examples', '_blank');
                    }
                }
            ]
        },
        {
            element: '#feature-guidechimp-chrome-extension',
            title: 'GuideChimp Chrome Extension',
            description: 'Start guided tour on any website with GuideChimp Chrome Extension and ZERO! code.',
            buttons: [
                {
                    title: 'Install Chrome Extension',
                    class: 'NL_button button_main NL_dark_btn NL_wide_btn',
                    onClick: function () {
                        window.open('https://www.labs64.com/guidechimp/', '_blank');
                    }
                }
            ]
        },
        {
            element: '#guidechimp-github',
            title: 'GuideChimp is Open Source',
            description: 'If you like GuideChimp, give us a star on GitHub ⭐',
            buttons: [
                {
                    title: 'Star on GitHub',
                    class: 'NL_button button_main NL_dark_btn NL_wide_btn',
                    onClick: function () {
                        window.open('https://github.com/Labs64/GuideChimp/stargazers', '_blank');
                    }
                }
            ]
        }
    ];
    var guideChimp = GuideChimp(tourGuideChimp);
    document.querySelector('#guidechimp-demo').onclick = function () {
        guideChimp.start();
    };
    var beacons = [{
        element: '#guidechimp-demo',
        position: 'top-left',
        boundary: 'outer',
        class: 'beacon-white',
        onClick() {
            guideChimp.start();
        },
    }];
    var guideChimpBeacon = GuideChimp.beacons(beacons, {
        boundary: 'outer'
    });
    guideChimpBeacon.showAll();
</script>

<style>
    .gc-tooltip {
        max-width: 450px;
    }

    .beacon-white {
        background-color: rgba(255, 255, 255, 1) !important;
    }
    .beacon-white:before {
        box-shadow: 0px 0px 3px 3px rgba(255, 255, 255, 0.7) !important;
    }
    .beacon-white.gc-beacon {
        background: linear-gradient(rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 1));
    }
</style>
