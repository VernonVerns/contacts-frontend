<template>
    <div class="side-bar">
        <ul class="list-unstyled">
            <li><router-link to="/">Dashboard</router-link></li>
            <li><router-link to="/" class="active-router">Contacts</router-link></li>
            <li><router-link to="/">Friends</router-link></li>
            <li><router-link to="/">Trash</router-link></li>
        </ul>

        <div class="footer-options">
            <ul class="list-unstyled">
                <li><router-link to="/">Settings</router-link></li>
                <li><router-link to="/">Support</router-link></li>
                <hr />
                <li class="developer">
                    <router-link to="/" class="details">
                        <div class="avatar">
                            <img src="../assets/img/simamkele.jpg" alt="">
                        </div>
                        <div class="name-and-position">
                            <h3 class="name">Simamkele Ndabeni</h3>
                            <h5 class="position">Application Developer</h5>
                        </div>
                    </router-link>
                </li>
            </ul>
        </div>
    </div>
</template>