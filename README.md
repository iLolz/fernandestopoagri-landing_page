# Fernandes Topografia e Agrimensura - Landing Page

This repository contains a single-page landing website for **Fernandes Topografia e Agrimensura**, built with plain HTML, CSS, and JavaScript.

## Current structure (validated from `index.html`)

- `Header/Topbar` with brand, WhatsApp CTA, and "Solicitar orçamento" anchor
- `Hero` with value proposition, trust bullets, and primary CTAs
- `Serviços` section with 6 service cards:
  - Levantamento Planialtimétrico e Cadastral
  - Locação e Acompanhamento de Obra
  - Georreferenciamento de Imóveis
  - Regularização, REURB e Usucapião
  - Loteamentos e Projetos
  - Aerolevantamento com Drone
- `Como funciona` with 5 process steps
- `Depoimentos` and `Segmentos atendidos`
- `Instagram` section with 3 embedded posts (`iframe`) and profile link `@fernandestopoagri`
- `FAQ` with 5 accordion questions
- `CTA banner` for WhatsApp contact
- `Contato / Orçamento` form + direct contact card
- `Footer` with legal/contact placeholders
- Floating WhatsApp button, toast feedback, and privacy-policy modal

## Behavior implemented

- Sticky topbar state on scroll
- FAQ accordion open/close logic
- Form validation (`nome` and `telefone` required)
- WhatsApp message generation from form inputs and `window.open` redirect
- Phone input masking for Brazilian format
- Privacy modal open/close (button, overlay click, and `Esc`)
- Dynamic footer year

## Integrations and key links

- WhatsApp number used in CTAs and form submission: `+55 31 99927-4089`
- Instagram: `https://www.instagram.com/fernandestopoagri`
- Contact email currently shown: `contato@fernandestopoagri.com`

## Pending content placeholders (`TODO` still present)

- Canonical and Open Graph domain/image URLs
- JSON-LD business details (address, coordinates, area served, email)
- Real customer names/details in testimonials
- Coverage region (FAQ + contact info)
- Full address and CNPJ in footer
- Privacy policy contact email and last update date

## Files

- `index.html`: complete landing page (markup, style, and scripts in one file)
- `assets/`: icons used by favicon, apple touch icon, and page branding
