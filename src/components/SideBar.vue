<template>
    <v-navigation-drawer v-model="drawer" app color="white" mini-variant mini-variant-width="80" >
        <v-avatar class="d-block text-center mx-auto mt-4" size="40">
            <v-icon color="#49D4A0">fab fa-atlassian</v-icon>
        </v-avatar>
    </v-navigation-drawer>
</template>

<script>
export default {
    data: () =>({
        SelectItem: 0,
        drawer: null,
        items: [
            {icon: 'fas fa-plus'},
            { icon: 'fas fa-th-large' },
            { icon: 'fas fa-align-center' },
            { icon: 'fas fa-gitter' },
            { icon: 'fas fa-chart-line' },
        ],

    })
}
</script>

<style>
    .border {
        margin-left: 12px;
        margin-right: 12px;
        background: #49D9A0;
        border-radius:50%;
        text-decoration: none;
    }
    .v-list-item-group .v-list-item--active {
        color: white !important;
    }
</style>