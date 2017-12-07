--- 
permalink: /preview-components/header--simpel.html
layout: iframed 
title: Header--simpel.html
---
<header class="header header-extended" role="banner">

    <div class="portal-header">
        <div class="portal-header-inner">
            <a href="/" title="Home" aria-label="Home">
                <div class="logo" id="basic-logo"></div>
            </a>
        </div>
    </div>

    <div class="navbar solution-header">
        <div class="solution-heading">
            <em class="heading-text">
        <a href="/"
          title="Home"
          aria-label="Home">
          Solution Header from config
        </a>
      </em>
        </div>
        <button class="menu-btn">Menu</button>
    </div>

    <nav role="navigation" class="nav">
        <div class="nav-inner">

            <div class="nav-secondary">
                <ul class="unstyled-list nav-secondary-links">
                    <li>
                        <a href="" class="button button-primary">
                            Secondary priority link
                        </a>
                    </li>
                    <li>
                        <a href="" class="">
                            Easy to comprehend link
                        </a>
                    </li>
                </ul>
            </div>

            <div class="nav-tertiary">
                <ul class="unstyled-list nav-secondary-links">
                    <li>
                        <a href="">
                            Secondary priority link
                        </a>
                    </li>
                    <li>
                        <a href="" class="button button-small">
                            Easy to comprehend
                        </a>
                    </li>
                    <li>
                        <select name="options" id="options">
                            <option value>- Vælg -</option>
                            <option value="option1">Mulighed 1</option>
                            <option value="option2">Mulighed 2</option>
                            <option value="option3">Mulighed 3</option>
                        </select>
                    </li>

                </ul>
            </div>

            <button class="nav-close">

            </button>

            <ul class="nav-primary accordion">
                <li>
                    <button class="accordion-button nav-link" aria-expanded="false" aria-controls="extended-mega-nav-section-one">
                        <span>Section title</span>
                    </button>
                    <ul id="extended-mega-nav-section-one" class="nav-submenu megamenu grid-full">
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title longer</a>
                            </li>
                            <li>
                                <a href="#">A very long page title that goes onto two lines</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                    </ul>
                </li>
                <li>
                    <button class="accordion-button nav-link" aria-expanded="false" aria-controls="extended-mega-nav-section-two">
                        <span>Simple terms</span>
                    </button>
                    <ul id="extended-mega-nav-section-two" class="nav-submenu megamenu grid-full">
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title longer</a>
                            </li>
                            <li>
                                <a href="#">A very long page title that goes onto two lines</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                        <div class="megamenu-col">
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                            <li>
                                <a href="#">Subsection title</a>
                            </li>
                        </div>
                    </ul>
                </li>
                <li>

                    <a class="nav-link" href="javascript:void(0)">
                        <span>Distinct from each other</span>
                    </a>
                </li>
            </ul>

        </div>
    </nav>
</header>
<div class="overlay"></div>