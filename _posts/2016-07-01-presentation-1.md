---
title: Presentation 1
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: Slide 1
   slide-data: This is first slide
     
 - title: Slide 2
   slide-data: This is second slide

 - title: Slide 3
   slide-data: This is third slide
   
 - title: Upskilling Equinor Personnel on Prompt Engineering tools / AI
   slide-data: 
- **Introduction to AI/ML**: This topic will cover the basics of AI, history, and applications in various industries, including engineering, but specifically for O/G
- **Data is Centric**: Whether we use a model-based, data driven or hybrid methods, it is important to leverage system data to gain knowledge of the system and make educated choices for product and process improvements. 
- **Integrated Design**: As much as possible, feedback mechanisms will also help improve technology by integrating observations from the current system into actions and decisions. Both for real time and non real time applications
- **AI in Engineering**, Design and Development: This topic will cover the applications of AI in design and development, including generative design, simulation, and optimization. Also covering aspects of predictive maintenance, quality control and process optimization
- **Prompt** **Engineering** for Equinor: How can we leverage AI tools to help with daily on the job tasks? ChatGPT as an example
   
 - 
  
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
