---
title: "Refrences"
description: "Refrence page for my Knowledge Base Document"
tags: ["stained-glass", "CMPA", "portfolio"]
draft: false
---

import React from "react";

// Stained Glass Reference Page
// Single-file React component styled with Tailwind CSS

export default function StainedGlassReferences() {
  const references = [
    {
      title: "Stained Glass Association of America (SGAA)",
      description:
        "National organization with technical resources, safety guidelines, and membership information for stained glass artists and studios.",
      url: "https://www.sgaaonline.com/",
    },
    {
      title: "Bullseye Glass Company — Resources & Techniques",
      description:
        "Manufacturer of art glass with an extensive library of technique articles, glass compatibility guides, and kiln firing charts.",
      url: "https://www.bullseyeglass.com/",
    },
    {
      title: "Uroboros Glass — Technical & Color Catalog",
      description:
        "Historic American art glass manufacturer with catalogs and technique notes useful for color selection and product specs.",
      url: "https://uroboros.com/",
    },
    {
      title: "Art Glass Supply — Tools & Tutorials",
      description:
        "Retail supplier with how-to guides, tool recommendations (saws, grinders, soldering irons), and material lists for beginners.",
      url: "https://www.artglasssupplies.com/",
    },
    {
      title: "YouTube: Glass YouTubers (e.g., 'Black Cat Glass' & 'Drucker Stained Glass')",
      description:
        "Video tutorials are excellent for step-by-step demonstrations of cutting, foiling, soldering, and leading techniques.",
      url: "https://www.youtube.com/",
    },
    {
      title: "Lead Safety & Exposure Guidance — OSHA",
      description:
        "Official safety recommendations for lead handling, PPE, ventilation, and workplace exposure limits relevant to lead-came construction and older glass restoration.",
      url: "https://www.osha.gov/lead",
    },
    {
      title: "Copper Foil Technique — Instructions & Tips",
      description:
        "Overview of copper-foil stained glass technique, common pitfalls, and finishing tips (patina, cementing, cleaning).",
      url: "https://www.copperfoilstainedglass.com/",
    },
    {
      title: "Books: 'Stained Glass: An Illustrated Manual for the Beginner'",
      description:
        "A recommended beginner book that covers tools, materials, pattern transfer, cutting, foiling, and soldering basics. Check your local library or book retailers.",
      url: "https://www.worldcat.org/",
    },
    {
      title: "Glass Cutting & Grinder Safety — Manufacturer Guides",
      description:
        "Manufacturer pages for saw blades, grinders, and safety gear. Always consult the specific tool manual for safe operation and maintenance.",
      url: "https://www.dremel.com/",
    },
    {
      title: "Local Suppliers & Studios (example search)",
      description:
        "Search for local stained glass suppliers, studios, and classes (use queries like 'stained glass supply Dallas' or 'stained glass classes Dallas').",
      url: "https://www.google.com/search?q=stained+glass+supplies+dallas",
    },
  ];

  return (
    <main className="min-h-screen bg-gray-50 p-6 md:p-12 font-sans text-gray-900">
      <header className="max-w-4xl mx-auto mb-8">
        <h1 className="text-3xl md:text-4xl font-bold mb-2">Stained Glass — Reference & Resources</h1>
        <p className="text-md md:text-lg text-gray-700">
          A curated list of websites, organizations, suppliers, and safety resources useful for
          stained-glass makers — from beginners learning copper-foil to studios working in lead
          came and kilnformed glass.
        </p>
      </header>

      <section className="max-w-4xl mx-auto bg-white shadow-md rounded-xl p-6">
        <h2 className="text-2xl font-semibold mb-4">Reference List</h2>

        <ul className="space-y-4">
          {references.map((ref, idx) => (
            <li key={idx} className="p-4 border rounded-lg hover:shadow-sm transition-shadow">
              <a
                href={ref.url}
                target="_blank"
                rel="noreferrer"
                className="text-xl font-medium text-indigo-700 hover:underline"
              >
                {ref.title}
              </a>
              <p className="text-sm text-gray-600 mt-1">{ref.description}</p>
              <p className="mt-2 text-xs text-gray-500">Link: <span className="break-all">{ref.url}</span></p>
            </li>
          ))}
        </ul>

        <footer className="mt-6 text-sm text-gray-600">
          <p>
            Note: This page is a starting point — if you would like this exported as a static HTML
            file, a printable PDF, or a spreadsheet with these resources and contact columns, I can
            generate that for you.
          </p>
        </footer>
      </section>
    </main>
  );
}
