---
layout: page
---
<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
    {
        avatar: 'https://avatars.githubusercontent.com/u/88144943',
        name: 'Corwin',
        title: 'Maintainer',
        links: [
        { icon: 'github', link: 'https://github.com/CorwinDev' }
        ]
    },
    {
        avatar: 'https://avatars.githubusercontent.com/u/15818451',
        name: 'Tomás',
        title: 'Designer and Frontend Developer',
        links: [
        { icon: 'github', link: 'https://github.com/CorwinDev' }
        ]
    }
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      Meet the Team
    </template>
    <template #lead>
      Paymenter is built and maintained by a dedicated developers from around the world. We are passionate about creating powerful, open-source tools for everyone.
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers :members />
</VPTeamPage>

