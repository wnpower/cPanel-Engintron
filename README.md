<h1>cPanel Nginx Installer</h1>
<p>Este script instala y configura Nginx (provisto por Engintron)</p>
<p><strong>Modo de uso:</strong> wget&nbsp;https://raw.githubusercontent.com/wnpower/cPanel-Nginx/master/install_engintron.sh&nbsp;&amp;&amp; bash install_engintron.sh&nbsp;</p>
<ol>
<li>Verifica si existe otro plugin normalmente usado "nginxcp" y lo elimina antes</li>
<li>Baja e instala Engintron</li>
<li>Configura el cach&eacute; din&aacute;mico a 30 segundos</li>
<li>Para servidores con 1 IP p&uacute;blica, agrega una l&iacute;nea en custom_rules para evitar errores con CloudFlare:&nbsp;<a href="https://github.com/engintron/engintron/wiki/Engintron-&amp;-the-%22Custom-Rules%22-file-(for-Nginx)">https://github.com/engintron/engintron/wiki/Engintron-&amp;-the-%22Custom-Rules%22-file-(for-Nginx)</a></li>
</ol>
