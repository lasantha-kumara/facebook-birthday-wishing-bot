# Facebook birthday wishing app done by using Selenium Web Driver

<ul>
  <li>How this app works</li>
</ul>
<ol>
  <li>Get username and password from the env file</li>
  <li>Load chrome options, drivers and pass header as a normal browser to avoid bot detection.</li>
  <li>After getting to home page enter email and password and press enter.</li>
  <li>Tap into aria label using css selector and get all timelines.</li>
  <li>Copy the birthday message to clipboard as selenium can't pass emojis.</li>
  <li>Then paste the birthday message and press enter to send the birthday wish to that person.</li>
  <li>After that wait 10 seconds before closing the browser windows.</li>
</ol>

