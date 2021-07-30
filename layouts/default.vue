<template>
  <v-app 
  style="background-image:url('https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/3174e669321565.5b7d0df084c41.gif')" 
  light>

    
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
      :color="bg"
    >
      <v-spacer />
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
    

  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Profile & Info.',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Work & Extra Academic Experiences',
          to: '/inspire'
        },
        {
          icon: 'mdi-star',
          title: 'Extra Curricular Acivities & Certification',
          to: '/extraAcc'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  },
  mounted () {
    window.onscroll = () => {
      this.changeColor()
    }
  },
  methods: {
    changeColor () {
      if (
        document.body.scrollTop > 100 ||
        document.documentElement.scrollTop > 100
      ) {
        this.bg = 'white'
      } else {
        this.bg = 'transparent'
      }
    }
  }
}
</script>
