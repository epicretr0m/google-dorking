# google-dorking

## English

    Google Dorking for specific files:
        Using the operator filetype: : filetype:pdf to search for PDF files.
        Using the operator ext: : ext:doc to search for doc files.

    Searching in page titles:
        Using the operator intitle: : intitle:"index of" to find pages with "index of" in their title.

    Searching in URLs:
        Using the operator inurl: : inurl:admin to find pages with "admin" in their URL.

    Searching for similar sites:
        Using the operator related: : related:example.com to find similar sites to "example.com".

    Excluding terms:
        Using the operator - : site:example.com -term to exclude pages containing the specified term.

    Searching for specific links:
        Using the operator link: : link:example.com to find pages that contain a link to "example.com".

    Searching in file metadata:
        Using the operator intext:"metadata" : intext:"metadata" site:example.com to find pages containing specific metadata.

    Searching for directories:
        Using the operator intitle:"index of" : intitle:"index of" site:example.com to find directories and file lists on a specific site.

    Searching for vulnerable servers:
        Using the operator intitle:"Apache HTTP Server Test Page" : intitle:"Apache HTTP Server Test Page" to find potentially vulnerable Apache servers.

    Searching for confidential documents:
        Using the operator intext:"confidential" OR intext:"secret" : intext:"confidential" OR intext:"secret" site:example.com to find potentially confidential documents on a specific site.

    Searching for exposed passwords:
        Using the operator intext:"password" filetype:txt : intext:"password" filetype:txt to find text files containing passwords.

    Searching for pages with sensitive parameters:
        Using the operator inurl:"?id=" : inurl:"?id=" site:example.com to find pages with sensitive URL parameters.

    Searching for PDF documents containing specific keywords:
        Using the operator intext:"keyword" with filetype:pdf : intext:"confidential" filetype:pdf site:example.com to find PDF documents containing the keyword "confidential" on a specific site.

    Searching for backup directories:
        Using the operator intitle:"index of" AND intitle:"backup" : intitle:"index of" AND intitle:"backup" site:example.com to find backup directories on a specific site.

    Searching for pages vulnerable to SQL injection:
        Using the operator inurl:"page.php?id=" : inurl:"page.php?id=" site:example.com to find pages potentially vulnerable to SQL injection on a specific site.

    Searching for email addresses:
        site:example.com intext:@example.com : Searching for email addresses on the site example.com.

    Searching for phone numbers:
        intext:"phone number" site:example.com : Searching for pages containing the text "phone number" on the site example.com.

    Searching for IP addresses:
        intext:"IP address" site:example.com : Searching for pages containing the text "IP address" on the site example.com.

    Searching for phone numbers in contact pages:
        intext:"contact us" intext:"phone" site:example.com : Searching for contact pages containing the word "phone" on the site example.com.

    Searching for IP addresses in server logs:
        filetype:log intext:"IP address" site:example.com : Searching for log files containing the text "IP address" on the site example.com.

# Español

    Google Dorking para archivos específicos:
        Utilizando el operador filetype: : filetype:pdf para buscar archivos PDF.
        Utilizando el operador ext: : ext:doc para buscar archivos doc.

    Búsqueda en títulos de página:
        Utilizando el operador intitle: : intitle:"index of" para encontrar páginas con "index of" en su título.

    Búsqueda en URLs:
        Utilizando el operador inurl: : inurl:admin para encontrar páginas con "admin" en su URL.

    Búsqueda de sitios similares:
        Utilizando el operador related: : related:example.com para encontrar sitios similares a "example.com".

    Exclusión de términos:
        Utilizando el operador - : site:example.com -term para excluir páginas que contienen el término especificado.

    Búsqueda de enlaces específicos:
        Utilizando el operador link: : link:example.com para encontrar páginas que contienen un enlace a "example.com".

    Búsqueda en metadatos de archivos:
        Utilizando el operador intext:"metadata" : intext:"metadata" site:example.com para encontrar páginas que contienen metadatos específicos.

    Búsqueda de directorios:
        Utilizando el operador intitle:"index of" : intitle:"index of" site:example.com para encontrar directorios y listas de archivos en un sitio específico.

    Búsqueda de servidores vulnerables:
        Utilizando el operador intitle:"Apache HTTP Server Test Page" : intitle:"Apache HTTP Server Test Page" para encontrar servidores Apache potencialmente vulnerables.

    Búsqueda de documentos confidenciales:
        Utilizando el operador intext:"confidential" OR intext:"secret" : intext:"confidential" OR intext:"secret" site:example.com para encontrar documentos potencialmente confidenciales en un sitio específico.

    Búsqueda de contraseñas expuestas:
        Utilizando el operador intext:"password" filetype:txt : intext:"password" filetype:txt para encontrar archivos de texto que contienen contraseñas.

    Búsqueda de páginas con parámetros sensibles:
        Utilizando el operador inurl:"?id=" : inurl:"?id=" site:example.com para encontrar páginas con parámetros de URL sensibles.

    Búsqueda de documentos PDF que contienen palabras clave específicas:
        Utilizando el operador intext:"keyword" with filetype:pdf : intext:"confidential" filetype:pdf site:example.com para encontrar documentos PDF que contienen la palabra clave "confidential" en un sitio específico.

    Búsqueda de directorios de respaldo:
        Utilizando el operador intitle:"index of" AND intitle:"backup" : intitle:"index of" AND intitle:"backup" site:example.com para encontrar directorios de respaldo en un sitio específico.

    Búsqueda de páginas vulnerables a la inyección SQL:
        Utilizando el operador inurl:"page.php?id=" : inurl:"page.php?id=" site:example.com para encontrar páginas potencialmente vulnerables a la inyección SQL en un sitio específico.

    Búsqueda de direcciones de correo electrónico:
        site:example.com intext:@example.com : Búsqueda de direcciones de correo electrónico en el sitio example.com.

    Búsqueda de números de teléfono:
        intext:"phone number" site:example.com : Búsqueda de páginas que contienen el texto "phone number" en el sitio example.com.

    Búsqueda de direcciones IP:
        intext:"IP address" site:example.com : Búsqueda de páginas que contienen el texto "IP address" en el sitio example.com.

    Búsqueda de números de teléfono en páginas de contacto:
        intext:"contact us" intext:"phone" site:example.com : Búsqueda de páginas de contacto que contienen la palabra "phone" en el sitio example.com.

    Búsqueda de direcciones IP en registros de servidores:
        filetype:log intext:"IP address" site:example.com : Búsqueda de archivos de registro que contienen el texto "IP address" en el sitio example.com.

## Français 
// Google Dorking //

Recherche de fichiers spécifiques :

    Utilisation de l'opérateur filetype: : filetype:pdf pour rechercher des fichiers PDF.
    Utilisation de l'opérateur ext: : ext:doc pour rechercher des fichiers de type doc.

Recherche dans les titres de page :

    Utilisation de l'opérateur intitle: : intitle:"index of" pour trouver des pages avec "index of" dans leur titre.

Recherche dans les URL :

    Utilisation de l'opérateur inurl: : inurl:admin pour trouver des pages avec "admin" dans leur URL.

Recherche de sites similaires :

    Utilisation de l'opérateur related: : related:example.com pour trouver des sites similaires à "example.com".

Exclusion de termes :

    Utilisation de l'opérateur - : site:example.com -term pour exclure les pages contenant le terme spécifié.

Recherche de liens spécifiques :

    Utilisation de l'opérateur link: : link:example.com pour trouver des pages qui contiennent un lien vers "example.com

    Recherche dans les métadonnées des fichiers :
        Utilisation de l'opérateur intext:"metadata" : intext:"metadata" site:example.com pour trouver des pages contenant des métadonnées spécifiques.

    Recherche de répertoires :
        Utilisation de l'opérateur intitle:"index of" : intitle:"index of" site:example.com pour trouver des répertoires et des listes de fichiers sur un site spécifique.

    Recherche de serveurs vulnérables :
        Utilisation de l'opérateur intitle:"Apache HTTP Server Test Page" : intitle:"Apache HTTP Server Test Page" pour trouver des serveurs Apache potentiellement vulnérables.

    Recherche de documents confidentiels :
        Utilisation de l'opérateur intext:"confidential" OR intext:"secret" : intext:"confidential" OR intext:"secret" site:example.com pour trouver des documents potentiellement confidentiels sur un site spécifique.

    Recherche de mots de passe exposés :
        Utilisation de l'opérateur intext:"password" filetype:txt : intext:"password" filetype:txt pour trouver des fichiers texte contenant des mots de passe.

    Recherche de pages avec des paramètres sensibles :
        Utilisation de l'opérateur inurl:"?id=" : inurl:"?id=" site:example.com pour trouver des pages avec des paramètres d'URL sensibles.

Recherche de documents PDF contenant des mots-clés spécifiques :

    Utilisation de l'opérateur intext:"keyword" avec filetype:pdf : intext:"confidential" filetype:pdf site:example.com pour trouver des documents PDF contenant le mot-clé "confidential" sur un site spécifique.

Recherche de répertoires de sauvegardes :

    Utilisation de l'opérateur intitle:"index of" AND intitle:"backup" : intitle:"index of" AND intitle:"backup" site:example.com pour trouver des répertoires de sauvegardes sur un site spécifique.

Recherche de pages vulnérables à l'injection SQL :

    Utilisation de l'opérateur inurl:"page.php?id=" : inurl:"page.php?id=" site:example.com pour trouver des pages potentiellement vulnérables à l'injection SQL sur un site spécifique.

Recherche d'adresses e-mail :

    site:example.com intext:@example.com : Recherche d'adresses e-mail sur le site example.com.

    Recherche de numéros de téléphone :
        intext:"phone number" site:example.com : Recherche de pages contenant le texte "phone number" sur le site example.com.

    Recherche d'adresses IP :
        intext:"IP address" site:example.com : Recherche de pages contenant le texte "IP address" sur le site example.com.

    Recherche de numéros de téléphone dans les pages de contact :
        intext:"contact us" intext:"phone" site:example.com : Recherche de pages de contact contenant le mot "phone" sur le site example.com.

    Recherche d'adresses IP dans les journaux de serveur :
        filetype:log intext:"IP address" site:example.com : Recherche de fichiers journaux contenant le texte "IP address" sur le site example.com.
