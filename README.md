# Google Dork

## English 
- **Filetype-specific search**:
  - Using `filetype:` operator: `filetype:pdf` to search for PDF files.
  - Using `ext:` operator: `ext:doc` to search for doc files.

- **Title search**:
  - Using `intitle:` operator: `intitle:"index of"` to find pages with "index of" in their title.

- **URL search**:
  - Using `inurl:` operator: `inurl:admin` to find pages with "admin" in their URL.

- **Similar sites search**:
  - Using `related:` operator: `related:example.com` to find sites similar to "example.com".

- **Term exclusion**:
  - Using `-` operator: `site:example.com -term` to exclude pages containing the specified term.

- **Specific link search**:
  - Using `link:` operator: `link:example.com` to find pages that contain a link to "example.com".

- **File metadata search**:
  - Using `intext:"metadata"` operator: `intext:"metadata" site:example.com` to find pages containing specific metadata.

- **Directory search**:
  - Using `intitle:"index of"` operator: `intitle:"index of" site:example.com` to find directories and file lists on a specific site.

- **Vulnerable server search**:
  - Using `intitle:"Apache HTTP Server Test Page"` operator: `intitle:"Apache HTTP Server Test Page"` to find potentially vulnerable Apache servers.

- **Confidential documents search**:
  - Using `intext:"confidential" OR intext:"secret"` operator: `intext:"confidential" OR intext:"secret" site:example.com` to find potentially confidential documents on a specific site.

- **Exposed passwords search**:
  - Using `intext:"password" filetype:txt` operator: `intext:"password" filetype:txt` to find text files containing passwords.

- **Sensitive parameter search**:
  - Using `inurl:"?id="` operator: `inurl:"?id=" site:example.com` to find pages with sensitive URL parameters.

- **PDF document search with specific keywords**:
  - Using `intext:"keyword"` with `filetype:pdf` operator: `intext:"confidential" filetype:pdf site:example.com` to find PDF documents containing the keyword "confidential" on a specific site.

- **Backup directory search**:
  - Using `intitle:"index of" AND intitle:"backup"` operator: `intitle:"index of" AND intitle:"backup" site:example.com` to find backup directories on a specific site.

- **SQL injection vulnerable page search**:
  - Using `inurl:"page.php?id="` operator: `inurl:"page.php?id=" site:example.com` to find potentially SQL injection vulnerable pages on a specific site.

- **Email address search**:
  - `site:example.com intext:@example.com` : Search for email addresses on example.com.

- **Phone number search**:
  - `intext:"phone number" site:example.com` : Search for pages containing the text "phone number" on example.com.

- **IP address search**:
  - `intext:"IP address" site:example.com` : Search for pages containing the text "IP address" on example.com.

- **Phone numbers in contact pages search**:
  - `intext:"contact us" intext:"phone" site:example.com` : Search for contact pages containing the word "phone" on example.com.

- **IP addresses in server logs search**:
  - `filetype:log intext:"IP address" site:example.com` : Search for log files containing the text "IP address" on example.com.

## Español 
- **Búsqueda de archivos específicos**:
  - Utilizando el operador `filetype:`: `filetype:pdf` para buscar archivos PDF.
  - Utilizando el operador `ext:`: `ext:doc` para buscar archivos de tipo doc.

- **Búsqueda en títulos de página**:
  - Utilizando el operador `intitle:`: `intitle:"index of"` para encontrar páginas con "index of" en su título.

- **Búsqueda en URL**:
  - Utilizando el operador `inurl:`: `inurl:admin` para encontrar páginas con "admin" en su URL.

- **Búsqueda de sitios similares**:
  - Utilizando el operador `related:`: `related:example.com` para encontrar sitios similares a "example.com".

- **Exclusión de términos**:
  - Utilizando el operador `-`: `site:example.com -término` para excluir páginas que contienen el término especificado.

- **Búsqueda de enlaces específicos**:
  - Utilizando el operador `link:`: `link:example.com` para encontrar páginas que contienen un enlace a "example.com".

- **Búsqueda de metadatos de archivos**:
  - Utilizando el operador `intext:"metadatos"`: `intext:"metadatos" site:example.com` para encontrar páginas que contienen metadatos específicos.

- **Búsqueda de directorios**:
  - Utilizando el operador `intitle:"index of"`: `intitle:"index of" site:example.com` para encontrar directorios y listas de archivos en un sitio específico.

- **Búsqueda de servidores vulnerables**:
  - Utilizando el operador `intitle:"Apache HTTP Server Test Page"`: `intitle:"Apache HTTP Server Test Page"` para encontrar servidores Apache potencialmente vulnerables.

- **Búsqueda de documentos confidenciales**:
  - Utilizando el operador `intext:"confidencial" OR intext:"secreto"`: `intext:"confidencial" OR intext:"secreto" site:example.com` para encontrar documentos potencialmente confidenciales en un sitio específico.

- **Búsqueda de contraseñas expuestas**:
  - Utilizando el operador `intext:"contraseña" filetype:txt`: `intext:"contraseña" filetype:txt` para encontrar archivos de texto que contienen contraseñas.

- **Búsqueda de parámetros sensibles**:
  - Utilizando el operador `inurl:"?id="`: `inurl:"?id=" site:example.com` para encontrar páginas con parámetros de URL sensibles.

- **Búsqueda de documentos PDF con palabras clave específicas**:
  - Utilizando el operador `intext:"palabra clave"` con `filetype:pdf`: `intext:"confidencial" filetype:pdf site:example.com` para encontrar documentos PDF que contienen la palabra clave "confidencial" en un sitio específico.

- **Búsqueda de directorios de copia de seguridad**:
  - Utilizando el operador `intitle:"index of" AND intitle:"copia de seguridad"`: `intitle:"index of" AND intitle:"copia de seguridad" site:example.com` para encontrar directorios de copia de seguridad en un sitio específico.

- **Búsqueda de páginas vulnerables a la inyección SQL**:
  - Utilizando el operador `inurl:"page.php?id="`: `inurl:"page.php?id=" site:example.com` para encontrar páginas potencialmente vulnerables a la inyección SQL en un sitio específico.

- **Búsqueda de direcciones de correo electrónico**:
  - `site:example.com intext:@example.com` : Búsqueda de direcciones de correo electrónico en example.com.

- **Búsqueda de números de teléfono**:
  - `intext:"número de teléfono" site:example.com` : Búsqueda de páginas que contienen el texto "número de teléfono" en example.com.

- **Búsqueda de direcciones IP**:
  - `intext:"dirección IP" site:example.com` : Búsqueda de páginas que contienen el texto "dirección IP" en example.com.

- **Búsqueda de números de teléfono en páginas de contacto**:
  - `intext:"contacto" intext:"teléfono" site:example.com` : Búsqueda de páginas de contacto que contienen la palabra "teléfono" en example.com.

- **Búsqueda de direcciones IP en registros de servidor**:
  - `filetype:log intext:"dirección IP" site:example.com` : Búsqueda de archivos de registro que contienen el texto "dirección IP" en example.com.

## Français 
- **Recherche de fichiers spécifiques**:
  - Utilisation de l'opérateur `filetype:` : `filetype:pdf` pour rechercher des fichiers PDF.
  - Utilisation de l'opérateur `ext:` : `ext:doc` pour rechercher des fichiers de type doc.

- **Recherche dans les titres de page**:
  - Utilisation de l'opérateur `intitle:` : `intitle:"index of"` pour trouver des pages avec "index of" dans leur titre.

- **Recherche dans les URL**:
  - Utilisation de l'opérateur `inurl:` : `inurl:admin` pour trouver des pages avec "admin" dans leur URL.

- **Recherche de sites similaires**:
  - Utilisation de l'opérateur `related:` : `related:example.com` pour trouver des sites similaires à "example.com".

- **Exclusion de termes**:
  - Utilisation de l'opérateur `-` : `site:example.com -terme` pour exclure les pages contenant le terme spécifié.

- **Recherche de liens spécifiques**:
  - Utilisation de l'opérateur `link:` : `link:example.com` pour trouver des pages qui contiennent un lien vers "example.com".

- **Recherche dans les métadonnées des fichiers**:
  - Utilisation de l'opérateur `intext:"métadonnées"` : `intext:"métadonnées" site:example.com` pour trouver des pages contenant des métadonnées spécifiques.

- **Recherche de répertoires**:
  - Utilisation de l'opérateur `intitle:"index of"` : `intitle:"index of" site:example.com` pour trouver des répertoires et des listes de fichiers sur un site spécifique.

- **Recherche de serveurs vulnérables**:
  - Utilisation de l'opérateur `intitle:"Apache HTTP Server Test Page"` : `intitle:"Apache HTTP Server Test Page"` pour trouver des serveurs Apache potentiellement vulnérables.

- **Recherche de documents confidentiels**:
  - Utilisation de l'opérateur `intext:"confidentiel" OR intext:"secret"` : `intext:"confidentiel" OR intext:"secret" site:example.com` pour trouver des documents potentiellement confidentiels sur un site spécifique.

- **Recherche de mots de passe exposés**:
  - Utilisation de l'opérateur `intext:"mot de passe" filetype:txt` : `intext:"mot de passe" filetype:txt` pour trouver des fichiers texte contenant des mots de passe.

- **Recherche de paramètres sensibles**:
  - Utilisation de l'opérateur `inurl:"?id="` : `inurl:"?id=" site:example.com` pour trouver des pages avec des paramètres d'URL sensibles.

- **Recherche de documents PDF avec des mots-clés spécifiques**:
  - Utilisation de l'opérateur `intext:"mot-clé"` avec `filetype:pdf` : `intext:"confidentiel" filetype:pdf site:example.com` pour trouver des documents PDF contenant le mot-clé "confidentiel" sur un site spécifique.

- **Recherche de répertoires de sauvegarde**:
  - Utilisation de l'opérateur `intitle:"index of" AND intitle:"sauvegarde"` : `intitle:"index of" AND intitle:"sauvegarde" site:example.com` pour trouver des répertoires de sauvegarde sur un site spécifique.

- **Recherche de pages vulnérables à l'injection SQL**:
  - Utilisation de l'opérateur `inurl:"page.php?id="` : `inurl:"page.php?id=" site:example.com` pour trouver des pages potentiellement vulnérables à l'injection SQL sur un site spécifique.

- **Recherche d'adresses e-mail**:
  - `site:example.com intext:@example.com` : Recherche d'adresses e-mail sur example.com.

- **Recherche de numéros de téléphone**:
  - `intext:"numéro de téléphone" site:example.com` : Recherche de pages contenant le texte "numéro de téléphone" sur example.com.

- **Recherche d'adresses IP**:
  - `intext:"adresse IP" site:example.com` : Recherche de pages contenant le texte "adresse IP" sur example.com.

- **Recherche de numéros de téléphone dans les pages de contact**:
  - `intext:"contact" intext:"téléphone" site:example.com` : Recherche de pages de contact contenant le mot "téléphone" sur example.com.

- **Recherche d'adresses IP dans les journaux du serveur**:
  - `filetype:log intext:"adresse IP" site:example.com` : Recherche de fichiers journaux contenant le texte "adresse IP" sur example.com.

