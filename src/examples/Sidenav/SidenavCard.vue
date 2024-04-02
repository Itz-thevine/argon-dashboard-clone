<script setup>

defineProps({
  card: {
    type: Object,
    required: true,
    title: String,
    description: String,
    links: {
      type: Array,
      label: String,
      route: String,
      color: String,
    },
  },
});
</script>

