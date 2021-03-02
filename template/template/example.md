You can access the values input by the user:

Value of Key: {{'{{'}} Key {{'}}'}}

----

You can access some metadata through the BOIL object:

{{'{%'}} for k,v in BOIL.items() {{'%}'}}
- {{'{{'}} k {{'}}'}} = {{'{{'}} v {{'}}'}}
{{'{%'}} endfor {{'%}'}}
