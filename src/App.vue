<template>
    <div id="app">
        <header>
            <nav class="uk-navbar-container" uk-navbar>
                <div class="uk-navbar-left">
    
                    <a class="uk-navbar-item uk-logo" href="#">Logo</a>
    
                    <ul class="uk-navbar-nav">
                        <li>
                            <a href="#">
                                <span class="uk-icon uk-margin-small-right" href="#" uk-icon="icon: star"></span>
                                Features
                            </a>
                        </li>
                    </ul>
    
                    <div class="uk-navbar-item">
                        <div>Some
                            <a href="#">Link</a>
                        </div>
                    </div>
    
                    <div class="uk-navbar-item">
                        <form action="javascript:void(0)">
                            <input class="uk-input uk-form-width-small" type="text" placeholder="Input">
                            <button class="uk-button uk-button-primary">Button</button>
                        </form>
                    </div>
    
                </div>
            </nav>
        </header>
        <section class="uk-flex">
            <div class="sidenav uk-width-1-5@s uk-section uk-section-secondary uk-padding-small">
                <ul class="uk-nav-default uk-nav-parent-icon" uk-nav>
                    <li class="uk-active">
                        <a href="#">Active</a>
                    </li>
                    <li class="uk-parent">
                        <a href="#">Parent</a>
                        <ul class="uk-nav-sub">
                            <li>
                                <a href="#">Sub item</a>
                            </li>
                            <li>
                                <a href="#">Sub item</a>
                            </li>
                        </ul>
                    </li>
                    <li class="uk-parent">
                        <a href="#">Parent</a>
                        <ul class="uk-nav-sub">
                            <li>
                                <a href="#">Sub item</a>
                            </li>
                            <li>
                                <a href="#">Sub item</a>
                            </li>
                        </ul>
                    </li>
                    <li class="uk-nav-header">Header</li>
                    <li>
                        <a href="#">
                            <span class="uk-margin-small-right" uk-icon="icon: table"></span> Item</a>
                    </li>
                    <li>
                        <a href="#">
                            <span class="uk-margin-small-right" uk-icon="icon: thumbnails"></span> Item</a>
                    </li>
                    <li class="uk-nav-divider"></li>
                    <li>
                        <a href="#">
                            <span class="uk-margin-small-right" uk-icon="icon: trash"></span> Item</a>
                    </li>
                </ul>
            </div>
            <div class="main uk-width-4-5 uk-padding" uk-height-viewport="offset-top: 20">
                <ul class="uk-subnav uk-subnav-pill" uk-margin>
                    <li class="uk-active">
                        <a href="#">Active</a>
                    </li>
                    <li>
                        <a href="#">Item</a>
                    </li>
                    <li>
                        <a href="#">More
                            <span uk-icon="icon:  triangle-down"></span>
                        </a>
                        <div uk-dropdown="mode: click;">
                            <ul class="uk-nav uk-dropdown-nav">
                                <li class="uk-active">
                                    <a href="#">Active</a>
                                </li>
                                <li>
                                    <a href="#">Item</a>
                                </li>
                                <li class="uk-nav-header">Header</li>
                                <li>
                                    <a href="#">Item</a>
                                </li>
                                <li>
                                    <a href="#">Item</a>
                                </li>
                                <li class="uk-nav-divider"></li>
                                <li>
                                    <a href="#">Item</a>
                                </li>
                            </ul>
                        </div>
                    </li>
                </ul>
    
                <div class="uk-child-width-1-2@s uk-grid-collapse uk-text-center" uk-grid>
                    <div>
                        <div class="uk-tile uk-tile-default">
                            <p class="uk-h4">Default</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-tile uk-tile-muted">
                            <p class="uk-h4">Muted</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-tile uk-tile-primary">
                            <p class="uk-h4">Primary</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-tile uk-tile-secondary">
                            <p class="uk-h4">Secondary</p>
                        </div>
                    </div>
                </div>
    
                <div class="uk-child-width-1-2@s" uk-grid>
                    <div>
                        <div uk-grid>
                            <div class="uk-width-auto@m">
                                <ul class="uk-tab-left" uk-tab="connect: #component-tab-left; animation: uk-animation-fade">
                                    <li>
                                        <a href="#">Active</a>
                                    </li>
                                    <li>
                                        <a href="#">Item</a>
                                    </li>
                                    <li>
                                        <a href="#">Item</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="uk-width-expand@m">
                                <ul id="component-tab-left" class="uk-switcher">
                                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</li>
                                    <li>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</li>
                                    <li>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur, sed do eiusmod.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div>
                        <div uk-grid>
                            <div class="uk-width-auto@m uk-flex-last@m">
                                <ul class="uk-tab-right" uk-tab="connect: #component-tab-right; animation: uk-animation-fade">
                                    <li>
                                        <a href="#">Active</a>
                                    </li>
                                    <li>
                                        <a href="#">Item</a>
                                    </li>
                                    <li>
                                        <a href="#">Item</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="uk-width-expand@m">
                                <ul id="component-tab-right" class="uk-switcher">
                                    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</li>
                                    <li>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</li>
                                    <li>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur, sed do eiusmod.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
    
                <div class="uk-child-width-1-2@s uk-grid-match" uk-grid>
                    <div>
                        <div class="uk-card uk-card-hover uk-card-body">
                            <h3 class="uk-card-title">Hover</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-card uk-card-default uk-card-hover uk-card-body">
                            <h3 class="uk-card-title">Default</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-card uk-card-primary uk-card-hover uk-card-body uk-light">
                            <h3 class="uk-card-title">Primary</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                    <div>
                        <div class="uk-card uk-card-secondary uk-card-hover uk-card-body uk-light">
                            <h3 class="uk-card-title">Secondary</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'app',
    data() {
        return {
        }
    },
    mounted() {
    }
}
</script>

<style lang="scss">

</style>
