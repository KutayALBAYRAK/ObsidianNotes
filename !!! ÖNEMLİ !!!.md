
TABLE file.mtime AS "Son Güncelleme", file.folder AS "Klasör"
WHERE contains(file.outlinks, [[!!!ÖNEMLİ!!!]])
SORT file.mtime DESC
