<?xml version="1.0" encoding="UTF-8"?>
<xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">

<xsl:template match="/">
  <html>
    <head>
      <title>Auto</title>
    </head>
    <body>
      <h1>Dettagli dell'auto</h1>
      <table border="1">
        <tr>
          <th>Nome</th>
          <th>Marca</th>
          <th>Modello</th>
          <th>Anno</th>
        </tr>
        <xsl:for-each select="autos/auto">
          <tr>
            <td><xsl:value-of select="@nome"/></td>
            <td><xsl:value-of select="marca"/></td>
            <td><xsl:value-of select="modello"/></td>
            <td><xsl:value-of select="anno"/></td>
          </tr>
        </xsl:for-each>
      </table>
    </body>
  </html>
</xsl:template>

</xsl:stylesheet>
