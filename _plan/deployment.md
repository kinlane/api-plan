---
class:
  - line
rel:
  - /rels/stop  
properties:
  sort: 3
  name: API Deployment
  description: This is the area of API design on this API transit system. Where you can learn all about, and be able to apply common web API design concepts.
entities:
  - class:
      - line
    rel:
      - /rels/area
    properties:
      - name: Requests
    links:
      - rel:
          - self
        href: /design/requests/               
links:
  - rel:
      - self
    href: /design/      
---
