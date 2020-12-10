<h2>Fonctions de base</h2>
<h3>Composer Magento</h3>

<p><strong>Gestion du cache</strong></p>
<p>
<code>php bin/magento cache:clean</code><br>             
<code>php bin/magento cache:disable</code><br>                  
<code>php bin/magento cache:enable</code> <br>                  
<code>php bin/magento cache:flush</code> <br>                  
<code>php bin/magento cache:status</code> <br>  
 </p>

<p><strong>Set up</strong></p>
<p>
<code> php bin/magento setup:backup</code><br>             
<code>php bin/magento setup:config:set</code><br>                  
<code>php bin/magento setup:db-data:upgrade</code> <br>                  
<codephp bin/magento setup:db-schema:upgrade </code> <br>                  
<code>php bin/magento setup:db:status</code> <br>
<code>php bin/magento setup:di:compile </code> <br>  
<code>php bin/magento setup:install</code> <br>  
<code>php bin/magento setup:performance:generate-fixtures</code> <br>  
<code>php bin/magento setup:rollback</code> <br>  
<code>php bin/magento setup:static-content:deploy</code> <br>  
<code>php bin/magento setup:store-config:set</code> <br>  
<code>php bin/magento setup:uninstall</code> <br>  
<code>php bin/magento setup:upgrade     </code> <br>  
</p>
 
<h3>Command Vagrant</h3>
<p><strong>Lancement de vangrant</strong></p>
<code>vagrant up</code>
<p><strong>Mise à jour du code de la VM à partir du local</strong></p>
<code>vagrant reload</code>
<code>vagrant rsync</code>
<p>Récupération code de la VM en local</p>
<code>vagrant rsync-back</code>

