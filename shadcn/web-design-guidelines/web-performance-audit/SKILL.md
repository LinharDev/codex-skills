---
name: web-performance-audit
description: Checklist de auditoria de performance web
---

# Web Performance Audit

Ao auditar um site:
1. **Core Web Vitals**: LCP < 2.5s, INP < 200ms, CLS < 0.1
2. **Imagens**: formato moderno (WebP/AVIF), dimensões corretas, lazy loading
3. **CSS/JS**: minificado, sem dependências inúteis, code splitting
4. **Fontes**: preconnect, font-display: swap, subset
5. **Cache**: headers corretos, service worker se PWA
6. **Bundle**: analisar com webpack-bundle-analyzer ou vite-bundle-visualizer
7. **Lighthouse**: rodar e reportar scores
8. Sugestões sempre com ação concreta e prioridade (alto/médio/baixo impacto)
