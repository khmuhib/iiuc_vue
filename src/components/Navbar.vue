<template>
  <nav>

    <ul class="menu-item">
      <li v-for="(item, i) in menu_item" :key="i">
        <a href="#">{{item.title}}</a>
      </li>
      <li>
        <Dropdown title="Services" :items="services" />
      </li>
    </ul>
    <div class="menu-item"><a href="#">Home</a></div>
    <div class="menu-item"><a href="#">About</a></div>
    <Dropdown title="Services" :items="services" />
    <div class="menu-item"><a href="#">Contact</a></div>
  </nav>
</template>

<script>
import Dropdown from './Dropdown';

export default {
  name: 'navbar-',
  components: {
    Dropdown
  },
  data () {
    return {
      services: [
        {
          title: 'Web',
          link: '#'
        },
        {
          title: 'Design',
          link:'#'
        },
        {
          title: 'Videos',
          link: '#'
        }
      ],
      menu_item: [
        {
          title: 'Home 01',
          link: '#'
        },
        {
          title: 'Home 02',
          link: '#'
        },
        {
          title: 'Home 03',
          link: '#'
        },
      ]

    }
  }
}
</script>

<style>
nav {
  display: flex;
  align-items: center;
  justify-content: center;
}

nav .menu-item {
  color: #FFF;
  padding: 10px 20px;
  position: relative;
  text-align: center;
  border-bottom: 3px solid transparent;
  display: flex;
  transition: 0.4s;
}

nav .menu-item.active,
nav .menu-item:hover {
  background-color: #444;
  border-bottom-color: #FF5858;
}

nav .menu-item a {
  color: inherit;
  text-decoration: none;
}
</style>