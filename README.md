<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Telugu Unicode to Non-Unicode Converter</title>
</head>
<body>

    <!-- ✅ Added line (ONLY this line is new) -->
    <div style="font-weight:bold; font-size:18px; margin-bottom:10px;">
        Developer name: Shiva
    </div>

    <h2>Telugu Unicode Input</h2>
    <textarea id="unicodeInput" rows="10" cols="50"></textarea><br>
    <button onclick="convertText()">Convert</button>
    <h2>Non-Unicode Output (e.g., Anu Font format)</h2>
    <textarea id="nonUnicodeOutput" rows="10" cols="50"></textarea>

    <script>
        function convertText() {
            const unicodeText = document.getElementById('unicodeInput').value;
            let nonUnicodeText = "";
            
            // The actual mapping logic for Telugu characters goes here.
            // This requires a comprehensive mapping of Unicode code points
            // to the specific character codes used by the target non-Unicode font.
            // This logic is complex and usually found in the linked GitHub projects.
            nonUnicodeText = "Conversion logic needs to be added from a library (e.g., Telugu-encoder)";
            
            document.getElementById('nonUnicodeOutput').value = nonUnicodeText;
        }
    </script>

</body>
</html>
