# Lista de Selectores CSS

<table class="selectorsReview">
<thead>
<tr>
	<th class="pattern">
		Selector
	</th>
	<th class="meaning">
		Significado
	</th>
	<th class="origin">
		Versión CSS
   </th>
</tr>
</thead>
<tbody>
<tr>
	<td class="pattern">*</td>
	<td class="meaning">
		<a href="#universal-selector">Cualquier elemento</a>
	</td>
	<td class="origin">2</td>
</tr>
	<tr>
	<td class="pattern">E</td>
	<td class="meaning">
		<a href="#type-selectors">Elementos con etiqueta <b>E</b></a>
 	</td>
	<td class="origin">1</td>
</tr>
<tr>
	<td class="pattern">E[foo]</td>
	<td class="meaning">
		<a href="#attribute-selectors">Elementos <b>E</b> con <b>foo</b> como atributo</a>
 	</td>
	<td class="origin">2</td>
</tr>
<tr>
	<td class="pattern">E[foo="bar"]
 	</td>
	<td class="meaning">
      <a href="#attribute-selectors">Elementos <b>E</b> con atributo <b>foo</b> con valor <b>bar</b></a>
 	</td>
	<td class="origin">2</td>
</tr>
<tr>
	<td class="pattern">E[foo~="bar"]</td>
	<td class="meaning">
		<a href="#attribute-selectors">
		an E element whose "foo" attribute value is a list of
      whitespace-separated values, one of which is exactly equal to "bar"
     </a>
 	</td>
	<td class="origin">2</td>
</tr>
<tr>
	<td class="pattern">E[foo^="bar"]</td>	
	<td class="meaning">
		<a href="#attribute-selectors">Elementos <b>E</b> con atributo <b>foo</b> cuyo valor inicia en <b>bar</b></a>
 	</td>
	<td class="origin">3</td>
</tr>
<tr>
	<td class="pattern">E[foo$="bar"]</td>
	<td class="meaning">
		<a href="#attribute-selectors">Elementos <b>E</b> con atributo <b>foo</b> cuyo valor termina en <b>bar</b></a>
 	</td>
 	</td>
	<td class="origin">3</td>
</tr>
<tr>
	<td class="pattern">E[foo*="bar"]</td>
	<td class="meaning">
      <a href="#attribute-selectors">Elementos <b>E</b> con atributo <b>foo</b> cuyo valor contiene como subcadena a <b>bar</b></a>
 	</td>
	<td class="origin">3</td>
</tr>
<tr>
	<td class="pattern">E[foo|="en"]
 	</td>
	<td class="meaning">
      <a href="#attribute-selectors">
				an E element whose "foo" attribute has a
      hyphen-separated list of values beginning (from the left) with "en"
      </a>
 	</td>
	<td class="origin">2</td>
</tr>
<tr>
	<td class="pattern">E:root</td>
	<td class="meaning">
		<a href="#structural-pseudos">Elementos <b>E</b>, donde <b>E</b> es un elemento raiz del documento</a>
 	</td>
	<td class="origin">3</td>
</tr>
<tr>
	<td class="pattern">E:nth-child(n)
 	</td>
	<td class="meaning">an E element, the n-th child of its parent
		<a href="#structural-pseudos">Elementos <b>E</b>, donde <b>E</b> es un elemento raiz del documento</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:nth-last-child(n)
 	</td>
	<td class="meaning">an E element, the n-th child of its parent, counting
      from the last one
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:nth-of-type(n)
 	</td>
	<td class="meaning">an E element, the n-th sibling of its type
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:nth-last-of-type(n)
 	</td>
	<td class="meaning">an E element, the n-th sibling of its type, counting
      from the last one
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:first-child
 	</td>
	<td class="meaning">an E element, first child of its parent
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">2
	</td>
</tr>
<tr>
	<td class="pattern">E:last-child
 	</td>
	<td class="meaning">an E element, last child of its parent
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:first-of-type
 	</td>
	<td class="meaning">an E element, first sibling of its type
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:last-of-type
 	</td>
	<td class="meaning">an E element, last sibling of its type
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3

	</td>
</tr>
<tr>
	<td class="pattern">E:only-child
 	</td>
	<td class="meaning">an E element, only child of its parent
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:only-of-type
 	</td>
	<td class="meaning">an E element, only sibling of its type
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:empty
 	</td>
	<td class="meaning">an E element that has no children (including text
      nodes)
 	</td>
	<td class="described"><a href="#structural-pseudos">Structural
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:link<br>
      E:visited
 	</td>
	<td class="meaning">an E element being the source anchor of a hyperlink of
      which the target is not yet visited (:link) or already visited
      (:visited)

 	</td>
	<td class="described"><a href="#link">The link pseudo-classes</a>

 	</td>
	<td class="origin">1

	</td>
</tr>
<tr>
	<td class="pattern">E:active<br>
      E:hover<br>
      E:focus
 	</td>
	<td class="meaning">an E element during certain user actions
 	</td>
	<td class="described"><a href="#useraction-pseudos">The user action
      pseudo-classes</a>

 	</td>
	<td class="origin">1 and 2
	</td>
</tr>
<tr>
	<td class="pattern">E:target

 	</td>
	<td class="meaning">an E element being the target of the referring URI
 	</td>
	<td class="described"><a href="#target-pseudo">The target pseudo-class</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:lang(fr)
 	</td>
	<td class="meaning">an element of type E in language "fr" (the document
      language specifies how language is determined)
 	</td>
	<td class="described"><a href="#lang-pseudo">The :lang() pseudo-class</a>

 	</td>
	<td class="origin">2
	</td>
</tr>
<tr>
	<td class="pattern">E:enabled<br>
      E:disabled
 	</td>
	<td class="meaning">a user interface element E which is enabled or
      disabled
 	</td>
	<td class="described"><a href="#UIstates">The UI element states
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E:checked<!--<br>E:indeterminate-->
 	</td>
	<td class="meaning">a user interface element E which is
      checked<!-- or in an
      indeterminate state--> (for instance a
      radio-button or checkbox)
 	</td>
	<td class="described"><a href="#UIstates">The UI element states
      pseudo-classes</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E::first-line
 	</td>
	<td class="meaning">the first formatted line of an E element
 	</td>
	<td class="described"><a href="#first-line">The ::first-line
      pseudo-element</a>
 	</td>
	<td class="origin">1
	</td>
</tr>
<tr>
	<td class="pattern">E::first-letter
 	</td>
	<td class="meaning">the first formatted letter of an E element
 	</td>
	<td class="described"><a href="#first-letter">The ::first-letter
      pseudo-element</a>
 	</td>
	<td class="origin">1
	</td>
</tr>
<tr>
	<td class="pattern">E::before
 	</td>
	<td class="meaning">generated content before an E element
 	</td>
	<td class="described"><a href="#gen-content">The ::before
      pseudo-element</a>
 	</td>
	<td class="origin">2
	</td>
</tr>
<tr>
	<td class="pattern">E::after
 	</td>
	<td class="meaning">generated content after an E element
 	</td>
	<td class="described"><a href="#gen-content">The ::after
      pseudo-element</a>
 	</td>
	<td class="origin">2
	</td>
</tr>
<tr>
	<td class="pattern">E.warning
 	</td>
	<td class="meaning">an E element whose class is "warning" (the document
      language specifies how class is determined).
 	</td>
	<td class="described"><a href="#class-html">Class selectors</a>
 	</td>
	<td class="origin">1
	</td>
</tr>
<tr>
	<td class="pattern">E#myid
 	</td>
	<td class="meaning">an E element with ID equal to "myid".
 	</td>
	<td class="described"><a href="#id-selectors">ID selectors</a>
 	</td>
	<td class="origin">1
	</td>
</tr>
<tr>
	<td class="pattern">E:not(s)
 	</td>
	<td class="meaning">an E element that does not match simple selector s
 	</td>
	<td class="described"><a href="#negation">Negation pseudo-class</a>
 	</td>
	<td class="origin">3
	</td>
</tr>
<tr>
	<td class="pattern">E F
 	</td>
	<td class="meaning">an F element descendant of an E element
 	</td>
	<td class="described"><a href="#descendant-combinators">Descendant
      combinator</a>
 	</td>
	<td class="origin">1
	</td>
</tr>
<tr>
	<td class="pattern">E &gt; F

 	</td>
	<td class="meaning">an F element child of an E element

 	</td>
	<td class="described"><a href="#child-combinators">Child combinator</a>

 	</td>
	<td class="origin">2
	</td>
</tr>
<tr>
	<td class="pattern">E + F
 	</td>
	<td class="meaning">an F element immediately preceded by an E element

	</td>
	<td class="described">
		<a href="#adjacent-sibling-combinators">Adjacent sibling combinator</a>
	</td>
	<td class="origin">
		2
	</td>
</tr>
<tr>
	<td class="pattern">
		E ~ F
	</td>
	<td class="meaning">
		an F element preceded by an E element
	</td>
	<td class="described">
		<a href="#general-sibling-combinators">General sibling combinator</a>
	</td>
	<td class="origin">3</td>
 </tr>
 </tbody></table>

### Fuente:

 - <http://www.w3.org/TR/css3-selectors/#selectors>