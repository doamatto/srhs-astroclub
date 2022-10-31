+++
title= "Cosmo— Our mascot"
+++

### Cosmo art
<div id="gdpr">
	<p>This website values your privacy. By clicking the link below, this website may load trackers or other scripts and embeds that may harm your privacy. An alternative should be provided below this window.</p>
	<button id="iframe" class="btn">Consent to allowing this page to load this frame.</a>
</div>
<p>
	You can view all pictures tagged with #srhscosmo on <a href="https://www.instagram.com/explore/tags/srhscosmo">Instagram.com.</a>
</p>
<script>
	document.getElementById("gdpr").style.display = "block";
	document.getElementById("iframe").addEventListener("click", () => {
		var iframe = document.createElement("iframe");
		iframe.height = "500px";
		iframe.src = "https://www.instagram.com/explore/tags/srhscosmo/";
		document.getElementById("gdpr").insertAdjacentElement("afterend", iframe)
		document.getElementById("gdpr").style.display = "none";
	}, false);
</script>
