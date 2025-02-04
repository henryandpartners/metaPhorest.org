---
layout: doc
outline: deep
---
<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const director = [
  {
    name: 'Hideo Iwasaki',
    title: 'metaPhorest Director',
    desc: '<a href="hideo-iwasaki">More...</a>',
    avatar: '/images/hideo-iwasaki.jpg',
    links: [
      { icon: 'facebook', link: 'https://www.facebook.com/iwasaki.hideo.5' },
    ],
  }
]
const members = [
  {
    name: 'Tomoki Matsumura',
    title: 'Artist-in-Residence',
    desc: '<a href="tomoki-matsumura">More...</a>',
    avatar: 'https://www.github.com/tomoki11.png',
    links: [
      { icon: 'github', link: 'https://github.com/tomoki11' },
      { icon: 'x', link: 'https://x.com/tomokimatsumura' },
      { icon: 'instagram', link: 'https://www.instagram.com/tomoki__matsumura/' },
      { icon: 'facebook', link: 'https://www.facebook.com/tomoki.matsumura11/' },
    ],
  },
  {
    name: 'Henry Tan',
    title: 'Artist-in-Residence',
    desc: '<a href="henry-tan">More...</a>',
    avatar: 'https://www.github.com/henryandpartners.png',
    links: [
      { icon: 'github', link: 'https://github.com/henryandpartners' },
      { icon: 'x', link: 'https://www.twitter.com/cyberotic555' },
      { icon: 'instagram', link: 'https://www.instagram.com/cyberotic' },
      { icon: 'facebook', link: 'https://www.facebook.com/henryandpartners' },
    ],
  },
  {
    name: 'Georg Tremmel',
    title: 'Artist-in-Residence',
    desc: '<a href="georg-tremmel">More...</a>',
    avatar: 'https://www.github.com/trembl.png',
    links: [
      { icon: 'github', link: 'https://github.com/trembl' },
      { icon: 'x', link: 'https://x.com/trembl' },
      { icon: 'instagram', link: 'https://instagram.com/georg.tremmel' },
      { icon: 'facebook', link: 'https://fb.me/trembl' },
    ],
  },
]
</script>

# Director

<VPTeamMembers size="small" :members="director" />

<br />

# Members

<VPTeamMembers size="small" :members="members" />

