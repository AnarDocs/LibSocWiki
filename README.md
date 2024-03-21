# LibSocWiki
Libertarian Socialist Wiki

Start with [Libertarian_Socialist_Wiki Index](pages/Libertarian_Socialist_Wiki.md)

Original location: [https://libsoc-wiki.fandom.com/wiki/](https://libsoc-wiki.fandom.com/wiki/)

Pages downloaded from: [https://s3.amazonaws.com/wikia_xml_dumps/l/li/libsocwiki_pages_current.xml.7z](https://s3.amazonaws.com/wikia_xml_dumps/l/li/libsocwiki_pages_current.xml.7z)

Converted to Markdown using: [https://github.com/outofcontrol/mediawiki-to-gfm](https://github.com/outofcontrol/mediawiki-to-gfm)

Importing into MediaWiki -

```
7z x libsocwiki_pages_current.xml.7z
cd /var/www/html/mediawiki/maintenance # or whatever your location is
php importDump.php < libsocwiki_pages_full.xml
```

Status: Most links working. Images still absent.
