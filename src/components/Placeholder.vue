<script>
  export default {
    name: 'vue-treeselect--placeholder',
    inject: [ 'instance' ],

    render() {
      const { instance } = this

      return (
        <div class='vue-treeselect__placeholder'>
          { instance.placeholder }
        </div>
      )
    },
  }
</script>
