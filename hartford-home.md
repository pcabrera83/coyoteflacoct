---
layout: hartford-layout
title: Hartford | Coyote Flaco Hartford
description: Welcome to Coyote Flaco Hartford located in Hartford’s quiet southwest, we’ve been serving up quality Mexican food straight from our parent’s recipes since 1999. Also, we make great margaritas and when the weather is nice, you can sit outside on the patio. On those pesky, dreary winter days and it’s too cold to go outside, WE DELIVER!!
permalink: /hartford.html
---
<!-- Slider In Section -->
{% include cfh-slider.html %}
<!-- Call Out Section -->
{% include cfh-callout.html %}
<!-- Location Welcome Section -->
{% include cfh-welcome.html %}
<!-- Review Header Section -->
{% include reviews-header.html %}
<!-- Testimonials Section -->
{% include location-testimonials.html%}
<!-- Image Divider Section -->
{% include cfh-imgdivider.html %}
<!-- Weekly Specials Section -->
{% include cfh-wspecials.html %}
<!-- Footer Section -->
{% include cfh-footer.html %}

<div id="offcanvas" class="uk-offcanvas">
    <div class="uk-offcanvas-bar uk-offcanvas-bar-flip">
        <ul class="uk-nav uk-nav-parent-icon uk-nav-offcanvas" data-uk-nav>
            <!-- home menu  -->
            <li class="uk-parent uk-active" data-uk-dropdown>
                <a href="index.html">
                    Home
                </a>
            </li>
            <!-- Locations menu -->
            <li class="uk-parent" data-uk-dropdown>
                <a href="#">
                    Locations
                </a>
                <div class="uk-dropdown uk-dropdown-navbar uk-dropdown-width-1">
                    <div class="uk-grid uk-dropdown-grid">
                        <div class="uk-width-1-1">
                            <ul class="uk-nav uk-nav-navbar">
                                {% for item in site.data.navigation.locations %}
                                <li>
                                    <a href="{{ item.link }}">
                                        {{ item.name }}
                                    </a>
                                </li>
                                {% endfor %}
                            </ul>
                        </div>
                    </div>
                </div>
            </li>
            <!-- Menu -->
            <li class="uk-parent" data-uk-dropdown="" aria-haspopup="" aria-expanded=""><a href="#">Menu</a>
                <div class="uk-dropdown uk-dropdown-navbar uk-dropdown-width-1 uk-dropdown-bottom" aria-hidden="true"
                    tabindex="" style="top: 70px; left: 0px;">
                    <div class="uk-grid uk-dropdown-grid">
                        <div class="uk-width-1-1">
                            <ul class="uk-nav uk-nav-navbar">
                                <li>
                                    <a href="hartford-lunch.html">
                                        Lunch
                                    </a>
                                </li>
                                <li>
                                    <a href="hartford-dine-in.html">
                                        Dine In
                                    </a>
                                <li>
                                    <a href="hartford-takeout.html">
                                        Take Out
                                    </a>
                                </li>
                                <li>
                                    <a href="hartford-drinks.html">
                                        Drinks
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </li>
            <!-- Happy Hour -->
            <li class="uk-parent" data-uk-dropdown>
                <a href="happyhour.html">Happy Hour</a>
            </li>
            <!-- Reservations -->
            <li class="uk-parent" data-uk-dropdown>
                <a href="hartford-reservations.html">Reservations</a>
            </li>
            <!-- About Us  -->
            <li class="uk-parent" data-uk-dropdown>
                <a href="about-hartford.html">About Us</a>
            </li>
        </ul>
    </div>
</div>

{% include scripts.html %}