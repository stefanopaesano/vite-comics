<script>
export default {
    data() {
        return {

        };
    },
    methods: {

    }
}
</script>

<template>
    <footer>
        <div class="bar-cinque">

            <div class="my-buuton-footer">

                <button>
                      vai
                </button>

            </div>
            

            <ul>
                <li></li>
            </ul>

        </div>
    </footer>
</template>

<style lang="scss" scoped>
.bar-cinque{
    border: 1px solid black;
    width: 100%;
    height: 100px;
    display: flex;
    background-color: rgb(60, 60, 60);

      .my-buuton-footer{
        display: flex;
        align-items: center;
        justify-content: center;
              button{
                width: 200px;
                height: 50px;
                margin-left: 100px;
              }
      }
   
}
</style>
