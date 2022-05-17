<script setup>
    import ContactCard from "../components/ContactCard.vue";
    import AddContact from "../components/modals/AddContact.vue"
</script>

<template>
    <div id="contacts_page">
        <div class="header-part">
            <div class="actions">
                <button class="main-btn" data-bs-toggle="modal" data-bs-target="#add_contact">Add Contact</button>
                <div class="dropdown">
                    <button class="main-btn" type="button" id="dropdownMenuButton2" data-bs-toggle="dropdown" aria-expanded="false">
                        All
                    </button>
                    <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="dropdownMenuButton2">
                      <li><a class="dropdown-item active" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Separated link</a></li>
                    </ul>
                </div>
                <div class="search-part">
                    <input type="search" name="search" id="search" placeholder="Search">
                    <button type="button">Search</button>
                </div>
            </div>
        </div>
        <div class="content">
            <div class="side-bar">

            </div>
            <div class="main-side">
                <h4 class="mini-title" data-bs-toggle="modal" data-bs-target="#success_error">Contacts list</h4>
                <div class="contacts-list">
                    <ContactCard />
                    <ContactCard />
                </div>
            </div>
        </div>
    </div>
    <AddContact />
</template>