<template>
    <header class="header-area-six fixed-top">
        <HederStyleTwo />

        <div class="nav-area-six">
            <div :class="['navbar-area', {'is-sticky': isSticky}]">
                <div class="main-nav">
                    <nav class="navbar navbar-expand-lg">
                        <div class="container-fluid">
                            <NuxtLink class="navbar-brand" to="/">
                                <img src="~/assets/images/logo-black.png" alt="image">
                            </NuxtLink>

                            <b-navbar-toggle target="navbarSupportedContent">
                                <span class="icon-bar top-bar"></span>
                                <span class="icon-bar middle-bar"></span>
                                <span class="icon-bar bottom-bar"></span>
                            </b-navbar-toggle>
                            
                            <b-collapse class="collapse navbar-collapse mean-menu" id="navbarSupportedContent" is-nav>
                                <ul class="navbar-nav m-auto">
                                    <li class="nav-item">
                                        <NuxtLink to="/#" class="nav-link">
                                            Home
                                            <i class='bx bx-chevron-right'></i>
                                        </NuxtLink>

                                        <ul class="dropdown-menu">
                                            <li class="nav-item">
                                                <NuxtLink to="/" class="nav-link" exact>
                                                    Home One
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/home-two" class="nav-link">
                                                    Home Two
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/home-three" class="nav-link">
                                                    Home Three
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/home-four" class="nav-link">
                                                    Home Four
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/home-five" class="nav-link">
                                                    Home Five
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/home-six" class="nav-link">
                                                    Home Six
                                                </NuxtLink>
                                            </li>
                                        </ul>
                                    </li>

                                    <li class="nav-item">
                                        <NuxtLink to="/about-us" class="nav-link">
                                            About Us
                                        </NuxtLink>
                                    </li>

                                    <li class="nav-item">
                                        <NuxtLink to="/#" class="nav-link">
                                            Pages 
                                            <i class='bx bx-chevron-right'></i>
                                        </NuxtLink>

                                        <ul class="dropdown-menu">
                                            <li class="nav-item">
                                                <NuxtLink to="/pricing" class="nav-link">
                                                    Pricing
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/testimonials" class="nav-link">
                                                    Testimonials
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/team" class="nav-link">
                                                    Team
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/faq" class="nav-link">
                                                    FAQ
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/#" class="nav-link">
                                                    User 
                                                    <i class='bx bx-chevron-right'></i>
                                                </NuxtLink>

                                                <ul class="dropdown-menu">
                                                    <li class="nav-item">
                                                        <NuxtLink to="/log-in" class="nav-link">
                                                            Log In
                                                        </NuxtLink>
                                                    </li>

                                                    <li class="nav-item">
                                                        <NuxtLink to="/sign-in" class="nav-link">
                                                            Sign In
                                                        </NuxtLink>
                                                    </li>

                                                    <li class="nav-item">
                                                        <NuxtLink to="/recover-password" class="nav-link">
                                                            Recover Password
                                                        </NuxtLink>
                                                    </li>
                                                </ul>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/terms-conditions" class="nav-link">
                                                    Terms & Conditions
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/privacy-policy" class="nav-link">
                                                    Privacy Policy
                                                </NuxtLink>
                                            </li>
                                        
                                            <li class="nav-item">
                                                <NuxtLink to="/error" class="nav-link">
                                                    Error Page
                                                </NuxtLink>
                                            </li>
                                        </ul>
                                    </li>

                                    <li class="nav-item">
                                        <NuxtLink to="/#" class="nav-link">
                                            Services 
                                            <i class='bx bx-chevron-right'></i>
                                        </NuxtLink>

                                        <ul class="dropdown-menu">
                                            <li class="nav-item">
                                            <NuxtLink to="/services-one" class="nav-link">
                                                Services One
                                            </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/services-two" class="nav-link">
                                                    Services One
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/services-three" class="nav-link">
                                                    Services One
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/services-details" class="nav-link">
                                                    Services Details
                                                </NuxtLink>
                                            </li>
                                        </ul>
                                    </li>

                                    <li class="nav-item">
                                        <NuxtLink to="/#" class="nav-link">
                                            Blog 
                                            <i class='bx bx-chevron-right'></i>
                                        </NuxtLink>

                                        <ul class="dropdown-menu">
                                            <li class="nav-item">
                                                <NuxtLink to="/news-grid" class="nav-link">
                                                    Blog Grid
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/blog-left-sidebar" class="nav-link">
                                                    Blog Left Sidebar
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/blog-right-sidebar" class="nav-link">
                                                    Blog Right Sidebar
                                                </NuxtLink>
                                            </li>

                                            <li class="nav-item">
                                                <NuxtLink to="/blog-details" class="nav-link">
                                                    Blog Details
                                                </NuxtLink>
                                            </li>
                                        </ul>
                                    </li>

                                    <li class="nav-item">
                                        <NuxtLink to="/contact" class="nav-link">
                                            Contact
                                        </NuxtLink>
                                    </li>
                                </ul>
                                
                                <div class="others-option">
                                    <div class="cart-icon">
                                        <NuxtLink to="/cart" class="cart">
                                            <i class="bx bx-shopping-bag"></i>
                                            <span>3</span>
                                        </NuxtLink >
                                    </div>

                                    <div class="sidebar-menu">
                                        <div class="burger-menu" v-b-modal.modal-1>
                                            <i class="bx bx-menu-alt-left"></i>
                                        </div>
                                    </div>
                               
                                    <SidebarModal />
                                </div>
                            </b-collapse>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
import HederStyleTwo from '../layouts/HederStyleTwo'
import SidebarModal from '../layouts/SidebarModal'

export default {
    name: 'NavbarStyleThree',
    components: {
        SidebarModal,
        HederStyleTwo
    },

    data(){
        return {
            isSticky: false
        }
    },

    mounted(){
        const that = this
        window.addEventListener('scroll', () => {
            let scrollPos = window.scrollY
            if(scrollPos >= 100){
                that.isSticky = true
            } else {
                that.isSticky = false
            }
        })
    }
}
</script>