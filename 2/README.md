# Project 2

## Title:

A reproducible workflow using Nextflow for protein Molecular Dynamics
(MD) simulations with documentation that supports RTL languages and
non-Latin scripts.

## Description:

The default language input for most open-source tools is
left-to-right. However, this excludes a vast community that
predominantly uses right-to-left (RTL) language and non-Latin scripts
such as Arabic, Urdu and Farsi. This project will create NextFlow
workflow and documentation that support RTL languages and non-Latin
scripts. NextFlow is a powerful and flexible workflow language that
enables the development of portable and reproducible workflows and
simplifies writing and deploying data-intensive computational
pipelines on any infrastructure. The nf-core community uses NetFlow to
develop highly optimised, portable, documented and easy-to-use
workflows pipelines and templates. However, all of the current nf-core
pipelines were developed for NGS data and none was developed for
structural biology or molecular dynamics workflows (MD). This project
will introduce a new workflow for molecular dynamics (MD) simulations
which are important tools for understanding the physical basis of the
structure and function of biological macromolecules. The workflow will
use different tools, including gromacs, gmx_MMPBSA, HeroMDAnalysis,
VMD, MDTraj and others.

The output of this project can be divided into 2 parts:

- Developing a workflow for protein Molecular Dynamics simulations. In
  order to produce tangible outcomes within the tight timeframe, we
  will exclude non-protein systems in the prototype of the
  workflow. This will be the 1st nf-core workflow that applies
  NextFlow to study protein dynamics.

- Implementing new functionality to support the documentation in RTL
  using a non-Latin script such as Arabic. In order to encourage the
  broad uses of this workflow and NextFlow in the MENA region, all the
  documentation will be provided in both Arabic and English. However,
  the nf-core template doesn’t yet support documentation in non-latin
  script or RTL languages. We will introduce a new feature in the
  nf-core to enable this new functionality. This will not just be
  applied in the Molecular Dynamics workflow pipeline but will also
  make nf-core (in general) more usable by non-English communities
  towards broader internationalisation of open source tools.

## Theme:

reproducible workflows for data analysis and interpretation (with
focus on Middle East)

## Team leader:
 * Name: Batool Almarzouq
 * Contact: batool@liverpool.ac.uk
 
## Submission number:

12
