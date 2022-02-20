body {
    padding: 1rem;
}

<form action="mailto:chriscoyier@gmail.com" method="GET" target="_blank">
    <h1 class="title">Start Email to chriscoyier@gmail.com</h1>
    <div class="field"><label class="label" for="subject">Email Subject</label>
        <input name="subject" id="subject" type="text" class="input" value="Example Email Subject"></div>
    <div class="field"><label class="label" for="body">Email Body</label>
        <textarea class="textarea" name="body" id="body">Example Email Body</textarea></div>
    <div><input type="submit" value="Create Email" class="button is-primary"></div>
</form>
