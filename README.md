<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cyber Toolkit</title>
<style>
body{
    background:#0d1117;
    color:#00ff88;
    font-family:monospace;
    padding:20px;
}
.container{
    max-width:700px;
    margin:auto;
    background:#161b22;
    padding:20px;
    border-radius:15px;
    box-shadow:0 0 20px rgba(0,255,136,0.2);
}
button{
    width:100%;
    padding:12px;
    margin:8px 0;
    border:none;
    border-radius:10px;
    background:#00ff88;
    color:black;
    font-weight:bold;
    cursor:pointer;
}
#output{
    margin-top:20px;
    padding:15px;
    background:black;
    min-height:120px;
    border-radius:10px;
}
</style>
</head>
<body>
<div class="container">
    <h1>CYBER TOOLKIT</h1>

    <button onclick="runTool('Network Scanner')">Network Scanner</button>
    <button onclick="runTool('Port Checker')">Port Checker</button>
    <button onclick="runTool('Password Strength')">Password Strength</button>
    <button onclick="runTool('Hash Generator')">Hash Generator</button>
    <button onclick="runTool('IP Info')">IP Info</button>

    <div id="output">System Ready...</div>
</div>

<script>
function runTool(tool){
    document.getElementById("output").innerHTML =
    "[+] Running " + tool + "...<br>[✓] Completed Successfully";
}
</script>
</body>
</html>
