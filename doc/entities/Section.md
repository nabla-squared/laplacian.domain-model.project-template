# **Section**
**namespace:** laplacian.project.document

section



---

## Properties

### name: `String`
The name of this section.
- **Attributes:** *PK*

### order: `Int`
The order of this section.
- **Default Value:**
  ```kotlin
  9999
  ```

## Relationships

### title: `MultilingualText`
title
- **Cardinality:** `1`

### content: `MultilingualText?`
content
- **Cardinality:** `0..1`

### sub_sections: `List<Section>`
sub_sections
- **Cardinality:** `*`

### parent_section: `Section?`
parent_section
- **Cardinality:** `0..1`