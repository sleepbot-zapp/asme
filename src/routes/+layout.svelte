<script>
	import "../app.css";
</script>

<body class="bg-zinc-800  w-500px font-bold">
<div>
  <ul class="flex justify-end text-xl mt-3 mr-4">
    <li><button class="rounded-xl h-10 w-15">Home</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-25">About Us</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-25">Commitee</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-35">Technical Teams</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-15">Blogs</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-15">Gallery</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="rounded-xl h-10 w-15">Contact</button></li>
    &nbsp;&nbsp;&nbsp;
    <li><button class="bg-blue-400 rounded-xl h-10 w-20 text-yellow-700">Log In</button></li>
  </ul>
</div>
<slot />
</body>