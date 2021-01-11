<html>
	
	<head>
		<title>
			Title!
		</title>
	</head>
	
	<body>
		<center>
			[ask a question here]
			<br>
			
			<div class="container">
                <label for="answer">Answer: </label>
                <input type="text" id="answer" name="answer">
                <button id="go" class="button">Check answer!</button>
            </div>
            
            <div id="output">
            <textarea readonly id="message"></textarea>
            </div>
		</center>
        
        <script>
            var question = 0;
            var ansField = document.getElementById("answer");
            var goButton = document.getElementById("go");
            var msg = document.getElementById("message");
            
            goButton.onclick = function() {
                ans = ansField.value
                if (ans === "Yes") {
                    msg.value = "Here is a message";
                }
                else {
                    msg.value = "???????????????????";
                }
            }
        </script>
	</body>
	
</html>
