var url = "https://api.fakeyou.com/tts/queue_length";

var XMLHttpRequest = require('xhr2');
var xhr = new XMLHttpRequest();
xhr.open("GET", url);
xhr.setRequestHeader("Content-Type", "application/json;charset=UTF-8");

xhr.onreadystatechange = function () {
    if (xhr.readyState === 4) {
        console.log(xhr.status);
        var resultText = xhr.responseText;
        console.log(resultText)
    }
};
xhr.send();


