# KIX-0
Clone des commandes <a href="https://www.gladir.com/SOFTWARE/KIX/presentation.htm">KIX</a> de Kyan Software pour l'Apple II en Pascal

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans KIX-0 :

<table>
	<tr>
		<th>Nom</th>
		<th>Description</th>	
	</tr>
     	<tr>
		<td><b>C40.PAS</b></td>
		<td>Cette commande permet de passer en écran de texte de 40 colonnes.</td>
	</tr>
	<tr>
		<td><b>C80.PAS</b></td>
		<td>Cette commande permet de passer en écran de texte de 80 colonnes.</td>
	</tr>	
	<tr>
		<td><b>CAT.PAS</b></td>
		<td>Cette commande permet d'afficher le contenu d'un/des fichiers. Cette commande est un équivalent de UNIX.</td>
	</tr>	
	<tr>
			<td><b>MV.PAS</b></td>
			<td>Cette commande permet de déplacer un fichier.</td>
		</tr>
   	<tr>
		<td><b>SD.PAS</b></td>
		<td>Cette commande permet d'imprimer le contenu de l'écran. Cette commande est inspiré du logiciel <a href="https://www.gladir.com/SOFTWARE/KIX/presentation.htm">KIX</a> de Kyan Software pour Apple II.</td>
	</tr>	
</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler COMMAND.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> COMMAND.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/KIX-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/KIX-0/blob/main/LICENSE">MIT</a>.</li>
</ul>
