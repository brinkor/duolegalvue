<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                    <router-link to="/" class="nav-link">Strona główna</router-link>
                    <router-link to="/about" class="nav-link">Usługi</router-link>
                    <router-link to="/team" class="nav-link">Zespół</router-link>
                    <router-link to="/contact" class="nav-link">Kontakt</router-link>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
