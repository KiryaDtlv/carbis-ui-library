<template>
  <v-container>
    <v-row class="text-center">
      <InputField>
        <template #prepend>
          <ToolTip></ToolTip>
        </template>
      </InputField>
      <PasswordField>
        <template #prepend>
          <ToolTip></ToolTip>
        </template>
      </PasswordField>
    </v-row>
  </v-container>
</template>

<script>
import PasswordField from "../CarbisUiLibrary/ui/PasswordField.vue";
import InputField from "../CarbisUiLibrary/ui/InputField.vue";
import ToolTip from "../CarbisUiLibrary/ui/ToolTip.vue";
export default {
  name: "HelloWorld",
  components: {
    PasswordField,
    InputField,
    ToolTip,
  },

  data: () => ({
    ecosystem: [
      {
        text: "vuetify-loader",
        href: "https://github.com/vuetifyjs/vuetify-loader",
      },
      {
        text: "github",
        href: "https://github.com/vuetifyjs/vuetify",
      },
      {
        text: "awesome-vuetify",
        href: "https://github.com/vuetifyjs/awesome-vuetify",
      },
    ],
    importantLinks: [
      {
        text: "Documentation",
        href: "https://vuetifyjs.com",
      },
      {
        text: "Chat",
        href: "https://community.vuetifyjs.com",
      },
      {
        text: "Made with Vuetify",
        href: "https://madewithvuejs.com/vuetify",
      },
      {
        text: "Twitter",
        href: "https://twitter.com/vuetifyjs",
      },
      {
        text: "Articles",
        href: "https://medium.com/vuetify",
      },
    ],
    whatsNext: [
      {
        text: "Explore components",
        href: "https://vuetifyjs.com/components/api-explorer",
      },
      {
        text: "Select a layout",
        href: "https://vuetifyjs.com/getting-started/pre-made-layouts",
      },
      {
        text: "Frequently Asked Questions",
        href: "https://vuetifyjs.com/getting-started/frequently-asked-questions",
      },
    ],
  }),
};
</script>
