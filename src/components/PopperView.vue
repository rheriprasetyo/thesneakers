<template>
    <div class="container">
        <div class="row">
            <div class="col">
               
                <Popper content="This is the Popper content 🍿">
                <button>Trigger element</button>
                </Popper>
                
            </div>
            <div class="col">
                <button type="button" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-html="true" title="<em>Tooltip</em> <u>with</u> <b>HTML</b>">
                Tooltip with HTML
                </button>
            </div>
            <div class="col">
                <div class="dropdown">
                <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                    Dropdown button
                </button>
                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                    <li><a class="dropdown-item" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
                </div>
            </div>
                <div class="col">
                <!-- Default dropup button -->
                <div class="btn-group dropup">
                    <button type="button" class="btn btn-secondary dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                        Dropup
                    </button>
                    <ul class="dropdown-menu">
                        <!-- Dropdown menu links -->
                        <li><a class="dropdown-item" href="#">Action</a></li>
                        <li><a class="dropdown-item" href="#">Another action</a></li>
                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                </div>
                </div>

        </div>
        
    </div>
</template>

<script>

import { defineComponent } from "vue";
import Popper from "vue3-popper";

  export default defineComponent({
     name: "PopperView",
    components: {
      Popper,
    },
  });



</script>

<style scoped>

</style>