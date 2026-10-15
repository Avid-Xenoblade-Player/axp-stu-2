<!DOCTYPE html>
<html>
  <head>
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="{{ '/style.css' | relative_url }}">
    <link rel="preconnect" href="https://fonts.bunny.net" />
		<link
			href="https://fonts.bunny.net/css?family=atkinson-hyperlegible:400,400i,500,500i,700,700i"
			rel="stylesheet"
		/>
  </head>
  <body>
    <div class="container">
      <div class="page-title">{{ page.title }}</div>
      <img class="comic-panel" src="{{ page.image | relative_url }}">
      <div class="narration">
        {{ content }}
      </div>
		
<a class="command-link" href="{{ page.next_page_url | relative_url }}">{{ page.next_page_title }}</a>
    </div>
    <!-- INPUT TERMINAL -->
    <div style="max-width: 650px; margin: 40px auto; padding: 15px; border: 2px dashed #000000; background-color: #550d51; font-family: 'Atkinson Hyperlegible', Courier, monospace; text-align: left;">
      <h3 style="margin-top: 0; text-align: center; font-size: 16px; font-weight: bold; background-color: #000000; color: #550d51; padding: 5px; letter-spacing: 1px;">
        INPUT TERMINAL
      </h3>
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf0vfz9sX2c-BUAixLRoTh-CdAiZWbh7zMyVe2ChpKtm9HuYA/viewform?embedded=true"
        width="100%" 
        height="450" 
        frameborder="0" 
        marginheight="0" 
        marginwidth="0"
        style="border: 2px solid #000000; background-color: #ad1aa4;">
        Loading interface terminal...
      </iframe>
    </div>
  </body>
</html>
