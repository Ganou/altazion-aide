# Stocks


<h2>Format Csv</h2><p>Permet d&#39;int&#233;grer les stocks d&#39;un d&#233;pot ou d&#39;un magasin.</p>


<table style='width:100%'><thead><tr><th>Champ</th><th>Type</th><th>Obligatoire</th><th style='width:50%'>Description</th></tr></thead><tbody><tr><td>depot_type</td><td>Enum</td><td><b>Oui</b></td><td>Type de d&#233;pot : &#39;DEPOT&#39; pour un stock d&#233;pot et &#39;MAG&#39; pour un stock magasin</td><td><tr><td>depot_code</td><td>Text</td><td>Non</td><td>Code du d&#233;pot/du magasin</td><td><tr><td>art_ref</td><td>Text</td><td><b>Oui</b></td><td>R&#233;f&#233;rence du produit</td><td><tr><td>type_ref</td><td>Text</td><td>Non</td><td>Si la r&#233;f&#233;rence dans {art_ref} n&#39;est pas le code principal de l&#39;article, pr&#233;cisez ici le type de r&#233;f&#233;rence (EAN13, ISBN, etc.)</td><td><tr><td>qte</td><td>Number</td><td><b>Oui</b></td><td>Quantit&#233; en stock</td><td></tbody></table>

