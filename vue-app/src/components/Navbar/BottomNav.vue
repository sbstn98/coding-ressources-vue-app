<template>
    <nav class="bg-white h-14">
        <div class="flex justify-between px-14 md:invisible">
            <RouterLink to="/">
                <NavBarIconHome />
            </RouterLink>
            <RouterLink to="/addnew">
                <NavBarIconAdd />
            </RouterLink>
            <RouterLink to="/user">
                <NavBarIconUser />
            </RouterLink>
        </div>

    </nav>
</template>


<script>
import NavBarIconHome from '@/components/Navbar/NavBarIconHome.vue';
import NavBarIconAdd from '@/components/Navbar/NavBarIconAdd.vue';
import NavBarIconUser from '@/components/Navbar/NavBarIconUser.vue';

export default {
    components: {
        NavBarIconHome,
        NavBarIconAdd,
        NavBarIconUser,
    },
};

</script>