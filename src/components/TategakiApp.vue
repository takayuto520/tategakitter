<template>
    <div class="container">
        <h1>たてがきったー</h1>
        <h2>縦書きツイートを作れるアプリ</h2>
        <div>
            <textarea id="input-area" placeholder="ここに入力してください" v-model="text"></textarea>
        </div>
        <div>
            <textarea id="output-area" placeholder="ここに出力されます" v-model="convert"></textarea>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            button_name: "buttttton",
            text: ""
        }
    },
    methods: {
        addItem: function() {
            console.log("Clicked!")
        }
    },
    computed: {
        convert: function() {
            var result = ""
            for(var i=0; i<this.text.length; i++){
                result += this.text.charAt(i) + "\n"
            }
            return result
        }
    }
}

</script>