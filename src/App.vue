<template>
  <f7-app>
    <f7-view main>
      <f7-page>
        <f7-navbar title="КП 2.2"></f7-navbar>

        <f7-block-title>Framework7 + Vue</f7-block-title>

        <f7-block strong>
          <p>Мій перший застосунок Framework7.</p>
        </f7-block>

        <f7-block>
          <f7-button fill>Кнопка</f7-button>
        </f7-block>
      </f7-page>
    </f7-view>
  </f7-app>
</template>

<script setup>
import {
  f7App,
  f7View,
  f7Page,
  f7Navbar,
  f7Block,
  f7BlockTitle,
  f7Button
} from 'framework7-vue'
</script>