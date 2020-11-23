# GrofLex

GRoninger OFfensive Lexicon (GrofLex) is a Dutch lexicon of abusive lemmas. It is created for a Bachelor Thesis in Information Science, at the University of Groningen. GrofLex is based on [HurtLex NL 1.2](https://github.com/valeriobasile/hurtlex/tree/master/lexica/NL/1.2).

## Fields

Most of the fields from HurtLex have been adopted to GrofLex, but two are removed and a new one is added.

### ID

A unique identifier for each lemma. Starts with the characters 'NL' and is followed by an integer.

### PoS

Universal Part-of-Speech tag for each lemma.

### Category

Three character abbreviation of the category the lemma belongs to.

<table>
<thead>
  <tr>
    <th>Category</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th colspan="2">Negative stereotypes</th>
  </tr>
  <tr>
    <td>ETH</td>
    <td>Ethnic slurs</td>
  </tr>
  <tr>
    <td>LOC</td>
    <td>Locations and demonyms</td>
  </tr>
  <tr>
    <td>PRO</td>
    <td>Professions and occupations</td>
  </tr>
  <tr>
    <td>PHY</td>
    <td>Physical disabilites and diversity</td>
  </tr>
  <tr>
    <td>COG</td>
    <td>Cognitive disabilities and diversity</td>
  </tr>
  <tr>
    <td>MOR</td>
    <td>Moral and behavioural defects</td>
  </tr>
  <tr>
    <td>SOC</td>
    <td>Words related to social and economic disadvantages</td>
  </tr>
  <tr>
    <td>SEX</td>
    <td>Words related to sexuality and gender</td>
  </tr>
  <tr>
    <td>REL</td>
    <td>Words related to religion</td>
  </tr>
  <tr>
    <th colspan="2">Hate words and slurs beyond stereotypes</th>
  </tr>
  <tr>
    <td>PLA</td>
    <td>Plants</td>
  </tr>
  <tr>
    <td>ANI</td>
    <td>Animals</td>
  </tr>
  <tr>
    <td>MGE</td>
    <td>Male genitalia</td>
  </tr>
  <tr>
    <td>FGE</td>
    <td>Female genitalia</td>
  </tr>
  <tr>
    <td>PRS</td>
    <td>Words related to prostitution</td>
  </tr>
  <tr>
    <td>DIS</td>
    <td>Words related to disease</td>
  </tr>
  <tr>
    <td>DER</td>
    <td>Derogatory words</td>
  </tr>
</tbody>
</table>

### Lemma

The abusive lemma.

### Num ID

Numerical ID matching the ID field (without 'NL') for easy sorting

# Authors

[Hylke van der Veen](https://www.linkedin.com/in/hylkevanderveen/)
