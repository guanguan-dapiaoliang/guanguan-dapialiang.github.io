<html>
    <head>
        <title>新年快乐</title><meta name="viewport" content="width=device-width"/>
        <script src="https://unpkg.com/vue/dist/vue.js"></script>
        <script src="https://unpkg.com/survey-vue@1.8.29/survey.vue.min.js"></script>
        <link href="https://unpkg.com/survey-knockout@1.8.29/modern.css" type="text/css" rel="stylesheet"/>
        <link rel="stylesheet" href="./index.css"></head>
    <body>
        <div id="surveyElement" style="display:inline-block;width:100%;">
            <survey :survey='survey'/>
        </div>
        <div id="surveyResult"></div>
        <script type="text/javascript" src="./index.js"></script>
    </body>
</html>
