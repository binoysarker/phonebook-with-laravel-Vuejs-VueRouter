<template>
        <nav class="panel is-offset-2 is-8">
            <p class="panel-heading">
                Phonebook
            </p>
            <div class="panel-block">
                <p class="control has-icons-left">
                    <input class="input is-small" type="text" placeholder="search">
                    <span class="icon is-small is-left">
        <i class="fa fa-search"></i>
      </span>
                </p>
            </div>

            <a class="panel-block is-active">
    <span class="panel-icon">
      <i class="fa fa-book"></i>
    </span>
                bulma
            </a>

            <label class="panel-block">
                <input type="checkbox">
                remember me
            </label>
            <div class="panel-block">
                <button class="button is-link is-outlined is-fullwidth">
                    reset all filters
                </button>
            </div>
        </nav>


</template>
<script >
    export default {

    }

</script>
<style>

</style>