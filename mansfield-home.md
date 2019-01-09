---
layout: mansfield-layout
title: Mansfield - Coyote Flaco Mansfield
description: Located in Storrs's, near the UCONN campus, we’ve been serving up quality Mexican food straight from our parent’s recipes since 2004. Also, we make great margaritas and when the weather is nice, you can sit outside on the patio. 
permalink: /mansfield.html
---
<!-- Slider In Section -->
{% include cfm-slider.html %}
<!-- Call Out Section -->
<!-- {% include cfm-callout.html %} -->
<!-- Location Welcome Section -->
{% include cfm-welcome.html %}
<!-- Review Header Section -->
{% include reviews-header.html %}
<!-- Testimonials Section -->
{% include location-testimonials.html%}
<!-- Image Divider Section -->
{% include cfm-imgdivider.html %}
<!-- Weekly Specials Section -->
{% include cfm-wspecials.html %}
<!-- Footer Section -->
{% include cfm-footer.html %}

<!-- offcanvas menu -->
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
                <li class="uk-parent" data-uk-dropdown="" aria-haspopup="true" aria-expanded="false"><a href="#">Menu</a>
                    <div class="uk-dropdown uk-dropdown-navbar uk-dropdown-width-1 uk-dropdown-bottom" aria-hidden="true"
                        tabindex="" style="top: 70px; left: 0px;">
                        <div class="uk-grid uk-dropdown-grid">
                            <div class="uk-width-1-1">
                                <ul class="uk-nav uk-nav-navbar">
                                    <!-- <li><a href="#">Lunch</a></li> -->
                                    <li><a href="mansfield-dine-in.html">Dine In</a>
                                        <!-- <li class="uk-parent"><a href="#">Dine In</a> -->
                                        <!-- <ul class="uk-nav-sub uk-dropdown-flip">
                                            <li><a href="">Appetizer</a></li>
                                            <li><a href="">Entreés</a></li>
                                            <li><a href="">Fajitas</a></li>
                                            <li><a href="">Combos</a></li>
                                            <li><a href="">Desserts</a></li>
                                            <li><a href="">Drinks</a></li>
                                        </ul> -->
                                        <!-- <li><a href="/mansfield-take-out.html">Take Out</a></li> -->
                                    <li><a href="mansfield-drinks.html">Drinks</a></li>
                </li>
        </ul>
    </div>
</div>
{% include scripts.html %}