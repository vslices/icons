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

The official VSlices icon represents the shared identity of the VSlices suite.

It should be used as the primary visual mark for VSlices and its connected products unless a more specific usage rule is defined later.

Product-specific differentiation should normally happen through naming, context, layout, or documentation structure rather than separate logos.

### Contextual product marks

A product may define a small contextual extension of the official VSlices mark when its runtime surface benefits materially from visual distinction, such as a browser toolbar icon. These marks should preserve the VSlices glyph as the dominant identity and add only the minimum product-specific motif required by the context.

Canonical contextual marks live under `products/<product>/`. Generated raster assets may be copied into product repositories when required by packaging or runtime tooling.

## Usage

Use the official icon for:

* documentation sites
* repository branding
* package metadata
* README headers
* generated documentation
* future VSlices tooling

When possible, prefer SVG for scalable usage and PNG for compatibility with tools that require raster images.

## Source of truth

This repository is the canonical source for VSlices iconography.

If an icon asset needs to be updated, update it here first and then propagate the generated files to the repositories that consume them.
