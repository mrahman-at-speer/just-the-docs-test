---
layout: default  
title: Pedigree File Layout  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Pedigree File Layout  
**Description**: Data schema for the pedigree file layout for the Resilient Dairy Genome Project  
**Classification**: RDF402  
**Schema package SAID**: EF_yLtvc7Z16eTbzjOy0ud4Wv4sZ_6V_eVyDCUFVwySI  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) |
| BIRTH_DATE | BIRTH_DATE |  |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). |
| FILE_TYPE | FILE_TYPE |  |
| PROJECT | PROJECT |  |
| REGISTERED_NAME | REGISTERED_NAME |  |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \"Source of Data\" column |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Pedigree File Layout | Data schema for the pedigree file layout for the Resilient Dairy Genome Project |

## Selection lists

### English

#### FILE_TYPE entry codes

| Entry code | Label |
| --- | --- |
| 01 | Pedigree |
| 02 | Calving |
| 03 | Production |
| 04 | Events |
| 05 | Genotype |
| 06 | Milk Data |

#### PROJECT entry codes

| Entry code | Label |
| --- | --- |
| 100 | EDGP |
| 110 | EDGP & RDGP |
| 111 | EDGP & RDGP & NAEX |
| 010 | RDGP |
| 011 | RDGP & NAEX |
| 001 | NAEX |
| 101 | EDGP & NAEX |

#### TRANSACTION_TYPE entry codes

| Entry code | Label |
| --- | --- |
| U | Update |
| D | Delete |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| ANIMAL_ID | false |  | Text | utf-8 | false |
| BIRTH_DATE | false |  | DateTime | utf-8 | false |
| DAM_ID | false |  | Text | utf-8 | true |
| FILE_TYPE | false |  | Text | utf-8 | false |
| PROJECT | false |  | Text | utf-8 | false |
| REGISTERED_NAME | false |  | Text | utf-8 | true |
| SIRE_ID | false |  | Text | utf-8 | true |
| SOURCE_OF_DATA | false |  | Text | utf-8 | false |
| TRANSACTION_TYPE | false |  | Text | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| ANIMAL_ID | ANIMAL_ID | INTERBULL REGISTRATION CODE WHICH HAS EXACTLY 19 CHARACTERS. MADE UP OF FOUR COMPONENTS: BREED (3), COUNTRY (3), SEX(1), REGISTRATION NUMBER(12) | Not a list |
| BIRTH_DATE | BIRTH_DATE |  | Not a list |
| DAM_ID | DAM_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). | Not a list |
| FILE_TYPE | FILE_TYPE |  | Pedigree, Calving, Production, Events, Genotype, Milk Data |
| PROJECT | PROJECT |  | EDGP, EDGP & RDGP, EDGP & RDGP & NAEX, RDGP, RDGP & NAEX, NAEX, EDGP & NAEX |
| REGISTERED_NAME | REGISTERED_NAME |  | Not a list |
| SIRE_ID | SIRE_ID | 12 DIGIT ALPHANUMERIC FIELD THAT CONTAIN THE UNIQUE IDENTIFICATION NUMBER ASSIGNED TO THE ANIMAL BY THE RESPECTIVE BREED ASSOCIATION. IT HAS TO BE RIGHT JUSTIFIED IN THE FIELD (WITH LEADING \'0\'S). | Not a list |
| SOURCE_OF_DATA | SOURCE_OF_DATA | See contacts list under \"Source of Data\" column | Not a list |
| TRANSACTION_TYPE | TRANSACTION_TYPE |  | Update, Delete |

## Schema SAIDs

**Capture base**: EKBa-ldXtgfZMXdjIwTeoccKLyJ9KlsDSIiPr737hh2R

**Bundle**: EM5MUOhiG17mesWDN0_t_VWtWll3vHKQj2WwvaHUOwy0

**Package**: EF_yLtvc7Z16eTbzjOy0ud4Wv4sZ_6V_eVyDCUFVwySI

| Layer | SAID | Type |
| --- | --- | --- |
| character_encoding | EIj4bv1fC5EW4jwyw_ovMhJsDItL85ZixNelORZSyLDW | spec/overlays/character_encoding/1.1 |
| conformance | ENKUvpp6xxWoeRjWxHWyoEsiapP_qQjqtF9wEEgz3dCe | spec/overlays/conformance/1.1 |
| entry (eng) | EMRlSrueg7Onp1-KUq2m7KLWYPl86h-RVeP7wFZqvNOQ | spec/overlays/entry/1.1 |
| entry_code | EEov_xnPMh2v2qUgTYZZ6tdJTOOdO4FBaW0hURSMGxcC | spec/overlays/entry_code/1.1 |
| information (eng) | EEyONuJsRYgqHQLts1YVQ2RCw5kfnag1BKRBEEEblFg3 | spec/overlays/information/1.1 |
| label (eng) | EBdKjDEVlcjirq6DfYxWpsxuWK56dtPvhQOKJTGV_XIn | spec/overlays/label/1.1 |
| meta (eng) | ENXWXXPkDubfnMP1WwuBhdtFWcRPgJGeQ3ghgMYy2ZxD | spec/overlays/meta/1.1 |
| ordering | EGRJbOTWmrQ1jRdVp-lGfTbp62Wm9j7AaQb7in3RGeFt | community/overlays/adc/ordering/1.1 |

**Date created**: 2025-04-16 17:12:54

