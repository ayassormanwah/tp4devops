# tp4devops
<html>
<body>
<h2>MASTER-2 BDCC, ENSET, 28/01/2023</h2>
<h3>Author : Manwah AYASSOR</h3>
<h2>Activité Pratique DEVOPS TP4</h2>

<ol>
    <li>Installer Jenkins<br/></li>
		<a href="https://www.jenkins.io/">https://www.jenkins.io/</a><br/>
		<a href="https://www.jenkins.io/download/">download</a><br/>
		<img src="captures/101-install-Jenkins.jpg" height="300px">
		<img src="captures/101-2-Jenkins.jpg" height="300px" border=1><br/>
    <li>Créer un projet « tp4 » contenant une page web index.html, qui affiche « Welcome BDCC » et un fichier de configuration docker au répertoire du projet (un docker file qui permet de lancer cette page sur un serveur web nginx).</li>
    	<h3>Projet TP4</h3>
    	<img src="captures/102-projet-tp4.jpg" width="400px"><br/>
    	<h3>Contenu du Dockerfile</h3>
    	<img src="captures/102-2-dockerfile.jpg" width="400px"><br/>
    	<!--Question3-->
    <li>Créer un répertoire Git hub nommée tp4 pour partager le code de l’application locale (tp4)</li>
        	<img src="captures/103-1-github.jpg" width="600px"><br/>
        	<ul>
        	<li>Initier Gît dans le répertoire du projet avec la commande <b>git init</b></li>
			<li>Ajouter tous les fichiers du projet au répertoire local avec la commande <b>git add *</b></li>
			<li><b>git config --global user.email</b> adresse email</li>
			<li>Enregistrer les changements dans le répertoire avec la commande <b>git commit -m “tp4 v1”</b></li>
			<li>Lier le répertoire local au répertoire git hub avec la commande <b>git remote add origin
				<a href="https://github.com/ayassormanwah/tp4devops.git">https://github.com/ayassormanwah/tp4devops.git</a></b></li>
			<li>Pusher le code vers le répertoire GitHub avec la commande <b>git push origin master</b></li>
        	</ul><br />
		<!--Question4-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
		<!--Question5-->
    <li>Ajouter des plugins docker à Jenkins</li>
        	<img src="captures/501-1-dockerplugins.jpg" width="800px"><br/>
		<!--Question6-->
    <li>Configurer job1tp4 afin de générer une image (docker build) et publier une image docker du projet sur docker hub (Tag latest).</li>
        	<img src="captures/601-1-general.jpg" width="800px"><br/>
        	<img src="captures/601-2-gestionducode.jpg" width="800px"><br/>
        	<img src="captures/601-3-declanchelebuild.jpg" width="800px"><br/>
        	<img src="captures/601-4-envdubuild.jpg" width="800px"><br/>
        	<img src="captures/601-5-buildsteps.jpg" width="800px"><br/>
        	<img src="captures/601-6-save.jpg" width="800px"><br/>
		<!--Question7-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
		<!--Question4-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
		<!--Question4-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
		<!--Question4-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
		<!--Question4-->
    <li>Créer et configurer un Job Jenkins (job1tp4) du type free style</li>
        	<img src="captures/401-1-job1tp4.jpg" width="800px"><br/>
    
	
</ol>
</body>
</html>