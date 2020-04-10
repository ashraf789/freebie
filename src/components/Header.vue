<template>
    <div class="container">
    <b-navbar>
        <template slot="brand">
            <b-navbar-item class="brand" tag="router-link" :to="{ path: '/' }">
                <span class="brand-first">App</span><span class="brand-second">Lab</span>
            </b-navbar-item>
        </template>
        <template slot="end">
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#feature">
                Key Features
            </b-navbar-item>
            <b-navbar-item href="#plan">
                Pricing
            </b-navbar-item>
            <b-navbar-item href="#testemonial">
                Testiminial
            </b-navbar-item>
            <b-navbar-item href="#faq">
                FAQ
            </b-navbar-item>
            <b-navbar-item href="#">
                <button class="button-blue button is-rounded">
                Try for free
                </button>
            </b-navbar-item>
        </template>
    </b-navbar>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>
<style scoped>
    .button-blue{
        height: 50px;
        width: 150px;
    }
    .navbar-item{
        margin: 10px!important;
        font-weight: 700;
    }
    .brand{
        font-size: larger;
    }
    .brand-first{
        color: darkorange;
    }
    .brand-second{
        color: black;
    }
</style>