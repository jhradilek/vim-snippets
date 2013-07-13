# RELAX NG Snippets for UltiSnips

The **rng.snippets** file provides a complete set of snippets for the RELAX NG schema language for XML according to [relaxng.rng](http://relaxng.org/relaxng.rng), version 1.31.

## Snippets for RELAX NG Elements

<table>
  <tr>
    <th>Trigger</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><strong>anyName</strong></td>
    <td><code>&lt;anyName /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>anyName</strong></td>
    <td><code>&lt;anyName&gt;...&lt;/anyName&gt;</code></td>
  </tr>
  <tr>
    <td><strong>attribute</strong></td>
    <td><code>&lt;attribute name="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>attribute</strong></td>
    <td><code>&lt;attribute name="..."&gt;...&lt;/attribute&gt;</code></td>
  </tr>
  <tr>
    <td><strong>attribute</strong></td>
    <td><code>&lt;attribute&gt;...&lt;/attribute&gt;</code></td>
  </tr>
  <tr>
    <td><strong>choice</strong></td>
    <td><code>&lt;choice&gt;...&lt;/choice&gt;</code></td>
  </tr>
  <tr>
    <td><strong>data</strong></td>
    <td><code>&lt;data type="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>data</strong></td>
    <td><code>&lt;data type="..."&gt;...&lt;/data&gt;</code></td>
  </tr>
  <tr>
    <td><strong>define</strong></td>
    <td><code>&lt;define name="..."&gt;...&lt;/define&gt;</code></td>
  </tr>
  <tr>
    <td><strong>define</strong></td>
    <td><code>&lt;define name="..." combine="..."&gt;...&lt;/define&gt;</code></td>
  </tr>
  <tr>
    <td><strong>div</strong></td>
    <td><code>&lt;div&gt;...&lt;/div&gt;</code></td>
  </tr>
  <tr>
    <td><strong>element</strong></td>
    <td><code>&lt;element name="..."&gt;...&lt;/element&gt;</code></td>
  </tr>
  <tr>
    <td><strong>element</strong></td>
    <td><code>&lt;element&gt;...&lt;/element&gt;</code></td>
  </tr>
  <tr>
    <td><strong>empty</strong></td>
    <td><code>&lt;empty /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>except</strong></td>
    <td><code>&lt;except&gt;...&lt;/except&gt;</code></td>
  </tr>
  <tr>
    <td><strong>externalRef</strong></td>
    <td><code>&lt;externalRef href="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>grammar</strong></td>
    <td><code>&lt;grammar xmlns="..." ns="..."&gt;...&lt;/grammar&gt;</code></td>
  </tr>
  <tr>
    <td><strong>grammar</strong></td>
    <td><code>&lt;grammar xmlns="..."&gt;...&lt;/grammar&gt;</code></td>
  </tr>
  <tr>
    <td><strong>grammar</strong></td>
    <td><code>&lt;grammar&gt;...&lt;/grammar&gt;</code></td>
  </tr>
  <tr>
    <td><strong>group</strong></td>
    <td><code>&lt;group&gt;...&lt;/group&gt;</code></td>
  </tr>
  <tr>
    <td><strong>include</strong></td>
    <td><code>&lt;include href="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>include</strong></td>
    <td><code>&lt;include href="..."&gt;...&lt;/include&gt;</code></td>
  </tr>
  <tr>
    <td><strong>interleave</strong></td>
    <td><code>&lt;interleave&gt;...&lt;/interleave&gt;</code></td>
  </tr>
  <tr>
    <td><strong>list</strong></td>
    <td><code>&lt;list&gt;...&lt;/list&gt;</code></td>
  </tr>
  <tr>
    <td><strong>mixed</strong></td>
    <td><code>&lt;mixed&gt;...&lt;/mixed&gt;</code></td>
  </tr>
  <tr>
    <td><strong>name</strong></td>
    <td><code>&lt;name&gt;...&lt;/name&gt;</code></td>
  </tr>
  <tr>
    <td><strong>notAllowed</strong></td>
    <td><code>&lt;notAllowed /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>nsName</strong></td>
    <td><code>&lt;nsName ns="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>nsName</strong></td>
    <td><code>&lt;nsName ns="..."&gt;...&lt;/nsName&gt;</code></td>
  </tr>
  <tr>
    <td><strong>oneOrMore</strong></td>
    <td><code>&lt;oneOrMore&gt;...&lt;/oneOrMore&gt;</code></td>
  </tr>
  <tr>
    <td><strong>optional</strong></td>
    <td><code>&lt;optional&gt;...&lt;/optional&gt;</code></td>
  </tr>
  <tr>
    <td><strong>param</strong></td>
    <td><code>&lt;param name="..."&gt;...&lt;/param&gt;</code></td>
  </tr>
  <tr>
    <td><strong>parentRef</strong></td>
    <td><code>&lt;parentRef name="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>ref</strong></td>
    <td><code>&lt;ref name="..." /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>start</strong></td>
    <td><code>&lt;start combine="..."&gt;...&lt;/start&gt;</code></td>
  </tr>
  <tr>
    <td><strong>start</strong></td>
    <td><code>&lt;start&gt;...&lt;/start&gt;</code></td>
  </tr>
  <tr>
    <td><strong>text</strong></td>
    <td><code>&lt;text /&gt;</code></td>
  </tr>
  <tr>
    <td><strong>value</strong></td>
    <td><code>&lt;value type="..."&gt;...&lt;/value&gt;</code></td>
  </tr>
  <tr>
    <td><strong>value</strong></td>
    <td><code>&lt;value&gt;...&lt;/value&gt;</code></td>
  </tr>
  <tr>
    <td><strong>zeroOrMore</strong></td>
    <td><code>&lt;zeroOrMore&gt;...&lt;/zeroOrMore&gt;</code></td>
  </tr>
</table>
