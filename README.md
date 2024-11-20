# Easy Slides - easy-slides.online


### Project structure

```
easy-slides/
├── frontend/ # Vue.js frontend
│ ├── Dockerfile
│ ├── src/
│ ├── public/
│ ├── package.json
│ ├── tailwind.config.js # Tailwind config file
│ └── postcss.config.js # PostCSS config file
├── backend/ # Go backend
│ ├── Dockerfile
│ ├── main.go
│ └── go.mod
├── nginx/ # Nginx config
│ └── nginx.conf
└── docker-compose.yml # Docker Compose configuration
```
Frontend uses vite for hot reload after file changes

---
##### PDF VUE 3
https://www.npmjs.com/package/pdf-vue3  
https://www.vuescript.com/minimal-pdf-viewer/  
PDF example:  
https://hymhub.github.io/pdf-vue3/