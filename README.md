<h1 id="fsage">NaN</h1>


{% for js in page.customjs %}
<script async type="text/javascript" src="{{ var today = new Date();
var birthDate = new Date(dateString);
var age = today.getFullYear() - birthDate.getFullYear();
var m = today.getMonth() - birthDate.getMonth();
if (m < 0 || (m === 0 && today.getDate() < birthDate.getDate())) {
age--;
}
document.getElementById("fsage").innerHTML = age; }}"></script>
{% endfor %}
