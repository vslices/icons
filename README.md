# VSlices Iconography

This repository contains the official iconography assets for **VSlices**.

It acts as the source of truth for the visual symbols used across the VSlices suite, including:

* VSlices
* VSlices Framework
* VSlices Design
* VSlices Docs Standard
* VSlices Method
* ActorChannel

## Purpose

The purpose of this repository is to keep VSlices icon assets centralized, consistent, and reusable across documentation sites, product repositories, packages, and future tooling.

Product repositories may copy generated assets locally when required by their documentation, build, publishing, or package tooling.

## Official icon

The official VSlices icon represents the shared visual identity of the VSlices suite.

It is the canonical visual mark from which product-specific iconography is composed.

The official mark should remain recognizable, materially intact, and visually dominant whenever it is used as part of a product icon.

## Product icons

Products, tools, applications, packages, documentation surfaces, or other things that belong to the VSlices ecosystem may define their own contextual iconography.

A VSlices product icon is not an independent logo. It is a composition of:

`official VSlices icon + graphical expression of the product`

The product-specific expression may communicate the product's purpose, interaction model, domain, or runtime context through secondary visual elements such as nodes, connections, overlays, framing, accents, composition, or other supporting motifs.

The official VSlices icon must remain the principal visual material in that composition.

A product-specific extension should not replace, obscure, deform beyond recognition, or visually overpower the official VSlices icon.

The intended reading order is:

`VSlices first -> product expression second`

This allows products to develop a recognizable expression of their own while preserving visual continuity across the VSlices suite.

### Review criteria

A product icon should normally be considered consistent with VSlices iconography when:

* the official VSlices icon is clearly recognizable;
* the official icon remains the dominant visual element;
* product-specific elements add contextual meaning rather than replacing the shared identity;
* the composition remains visually continuous with the rest of the VSlices ecosystem;
* removing the product-specific elements would still leave the canonical VSlices mark recognizable underneath the composition.

A product icon should be reconsidered when:

* the official VSlices icon disappears or becomes difficult to recognize;
* the product expression becomes the dominant visual identity;
* the result behaves as a separate logo that only loosely references VSlices;
* the composition introduces visual complexity that does not materially improve product recognition or meaning.

## Usage

Use the official icon directly when a shared VSlices identity is sufficient, including:

* repository branding;
* documentation and README headers;
* package metadata;
* generated documentation;
* generic VSlices tooling or surfaces without a meaningful product-specific visual expression.

Use a product icon when the surface materially benefits from distinguishing a specific VSlices product while retaining the shared VSlices identity, such as:

* browser or desktop application icons;
* extension toolbar icons;
* product-specific package or executable metadata;
* product navigation surfaces;
* application launchers;
* other compact visual contexts where product recognition matters.

When possible, prefer SVG for canonical scalable assets and PNG for compatibility with tools that require raster images.

## Source of truth

This repository is the canonical source for VSlices iconography.

The official VSlices mark belongs under `official/`.

Product-specific iconography should be maintained in an explicitly product-scoped location so that the relationship between the shared mark and its contextual expression remains visible and reviewable.

If an icon asset needs to be updated, update it here first and then propagate the generated files to the repositories that consume it.
