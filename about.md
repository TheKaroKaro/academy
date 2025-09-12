---
layout: default
title: About / Contact
description: Get in touch with Bread & Letters - Practical skills for ambitious young professionals in South East Asia.
---

<section class="max-w-3xl mx-auto px-4 py-16">
  <h1 class="text-3xl font-bold mb-8">About Bread & Letters</h1>
  
  <div class="prose prose-lg mb-12">
    <p>Bread & Letters was founded to address a specific need: young professionals in South East Asia often struggle to bridge the gap between academic knowledge and practical workplace skills.</p>
    
    <p>We create short, practical online sessions focused on presentation skills, Excel mastery, and workplace essentials—localized specifically for SEA audiences and contexts.</p>
    
    <p>Our instructors are industry professionals with extensive experience across the South East Asian market, ensuring our content is relevant and immediately applicable.</p>
  </div>
  
  <h2 class="text-2xl font-bold mb-6">Contact Us</h2>
  
  <div class="bg-gray-50 p-6 rounded-lg">
    <div class="grid md:grid-cols-2 gap-6">
      <div>
        <h3 class="font-semibold mb-2">Email</h3>
        <p><a href="mailto:{{ site.email }}" class="text-teal-600 hover:text-teal-800">{{ site.email }}</a></p>
      </div>
      
      <div>
        <h3 class="font-semibold mb-2">Follow Us</h3>
        <div class="flex space-x-4">
          {% if site.social.linkedin %}
          <a href="{{ site.social.linkedin }}" class="text-gray-600 hover:text-teal-600"><i class="fab fa-linkedin-in fa-lg"></i></a>
          {% endif %}
          {% if site.social.instagram %}
          <a href="{{ site.social.instagram }}" class="text-gray-600 hover:text-teal-600"><i class="fab fa-instagram fa-lg"></i></a>
          {% endif %}
          {% if site.social.twitter %}
          <a href="{{ site.social.twitter }}" class="text-gray-600 hover:text-teal-600"><i class="fab fa-twitter fa-lg"></i></a>
          {% endif %}
        </div>
      </div>
    </div>
    
    <div class="mt-6">
      <h3 class="font-semibold mb-2">Send us a message</h3>
      <form class="space-y-4" netlify>
        <div>
          <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Your Name</label>
          <input type="text" id="name" name="name" class="w-full px-4 py-2 border rounded-md" required>
        </div>
        
        <div>
          <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
          <input type="email" id="email" name="email" class="w-full px-4 py-2 border rounded-md" required>
        </div>
        
        <div>
          <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
          <textarea id="message" name="message" rows="4" class="w-full px-4 py-2 border rounded-md" required></textarea>
        </div>
        
        <button type="submit" class="px-5 py-3 bg-teal-600 text-white rounded font-medium">Send Message</button>
      </form>
    </div>
  </div>
</section>