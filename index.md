---
layout: default
title: SHI Collaboration Profiles
description: Profile pages for Sustainable Horizons Institute collaborators
---

# SHI Collaboration Profiles

## Our Collaborators

<div class="profiles-grid">
{% for profile in site.profiles %}
  <div class="profile-card">
    {% if profile.image %}
      <div class="profile-card-image">
        <img src="{{ profile.image | relative_url }}" alt="{{ profile.name }}" />
      </div>
    {% else %}
      <div class="profile-card-image-placeholder">
        <span>{{ profile.name | slice: 0 }}</span>
      </div>
    {% endif %}
    
    <div class="profile-card-content">
      <h3><a href="{{ profile.url | relative_url }}">{{ profile.name }}</a></h3>
      {% if profile.project_title %}
        <p class="profile-card-title">{{ profile.project_title }}</p>
      {% endif %}
      <p class="profile-card-org">{{ profile.organization }}</p>
      {% if profile.academic_interests %}
        <p class="profile-card-bio">{{ profile.academic_interests | truncate: 150 }}</p>
      {% endif %}
      
      <div class="profile-card-links">
        {% if profile.email %}
          <a href="mailto:{{ profile.email }}" title="Email {{ profile.name }}">📧</a>
        {% endif %}
        {% if profile.website %}
          <a href="{{ profile.website }}" title="Visit {{ profile.name }}'s website" target="_blank">🌐</a>
        {% endif %}
        {% if profile.github %}
          <a href="{{ profile.github }}" title="View {{ profile.name }}'s GitHub" target="_blank">🐙</a>
        {% endif %}
        {% if profile.linkedin %}
          <a href="{{ profile.linkedin }}" title="View {{ profile.name }}'s LinkedIn" target="_blank">💼</a>
        {% endif %}
      </div>
    </div>
  </div>
{% endfor %}
</div>

## About the Program

The Sustainable Horizons Institute (SHI) Building Engagement program supports researchers and practitioners from underrepresented communities in attending conferences, workshops, and other professional development opportunities in the field of research software engineering and high-performance computing.

### Program Goals

- Foster diversity and inclusion in research software engineering
- Support professional development opportunities
- Build community connections and mentorship
- Advance careers of underrepresented researchers
- Strengthen the overall research software engineering ecosystem

For more information about the program and how to get involved, please contact us.
