---
title: "Stained Glass Making"
description: "CMPA knowledge base for the semester-long stained glass project"
tags: ["stained-glass", "CMPA", "portfolio"]
draft: false
---

export default function StainedGlassGuide() {
  return (
    <div className="p-8 max-w-4xl mx-auto">
      <h1 className="text-3xl font-bold mb-6 text-center">
        Stained Glass Making: A Visual Guide
      </h1>
      <p className="mb-6 text-lg leading-relaxed">
        Stained glass making is a meticulous craft that combines artistry and technical skill. 
        This guide provides a visual overview of the process, from design to completion.
      </p>

      {/* Step 1 */}
      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-3">Step 1: Designing the Pattern</h2>
        <p className="mb-4">
          The process begins with creating a pattern, known as a <i>cartoon</i>, which serves 
          as a full-scale guide for the stained glass piece. This design outlines the shapes 
          and sizes of each glass piece.
        </p>
        <img
          src="https://i.pinimg.com/originals/90/2c/6d/902c6d89e36cbfe829af6f9fa9efb58e.jpg"
          alt="Stained Glass Pattern Design"
          className="rounded-xl shadow-lg mx-auto mb-2"
        />
        <p className="text-sm text-gray-600 text-center">Example of a stained glass pattern design.</p>
      </section>

      {/* Step 2 */}
      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-3">Step 2: Selecting and Cutting the Glass</h2>
        <p className="mb-4">
          Once the pattern is ready, glass sheets are selected based on color and texture. 
          Using a glass cutter, the glass is scored and then snapped along the lines to 
          match the pattern.
        </p>
        <img
          src="https://i0.wp.com/www.delphiglass.com/blog/wp-content/uploads/2012/04/GlassCutting.jpg"
          alt="Cutting stained glass pieces"
          className="rounded-xl shadow-lg mx-auto mb-2"
        />
        <p className="text-sm text-gray-600 text-center">Cutting glass pieces to match the pattern.</p>
      </section>

      {/* Step 3 */}
      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-3">Step 3: Leading and Soldering</h2>
        <p className="mb-4">
          The cut glass pieces are then arranged and held together using lead came. 
          The joints are soldered to secure the pieces in place.
        </p>
        <img
          src="https://i0.wp.com/www.stainedglasslondon.com/wp-content/uploads/2016/03/soldering-stained-glass.jpg"
          alt="Soldering stained glass"
          className="rounded-xl shadow-lg mx-auto mb-2"
        />
        <p className="text-sm text-gray-600 text-center">Soldering lead joints to hold the glass pieces.</p>
      </section>

      {/* Step 4 */}
      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-3">Step 4: Cementing and Finishing</h2>
        <p className="mb-4">
          The assembled piece is cemented to waterproof and strengthen the joints. 
          After cleaning off excess cement, the glass is polished to enhance its brilliance.
        </p>
        <img
          src="https://i0.wp.com/www.creativeglassguild.co.uk/media/wysiwyg/stained_glass_cement.jpg"
          alt="Cementing stained glass panel"
          className="rounded-xl shadow-lg mx-auto mb-2"
        />
        <p className="text-sm text-gray-600 text-center">Cementing and finishing the stained glass artwork.</p>
      </section>

      {/* Visual Reference */}
      <section className="mb-12 text-center">
        <h2 className="text-2xl font-semibold mb-3">Visual Reference</h2>
        <img
          src="https://www.instructables.com/files/deriv/FFK/8ZQ8/HS6W1V5F/FFK8ZQ8HS6W1V5F.LARGE.jpg"
          alt="Stained Glass Making Process"
          className="rounded-xl shadow-lg mx-auto mb-3"
        />
        <p className="text-sm text-gray-600">
          Image Source:{" "}
          <a
            href="https://www.instructables.com/How-To-Stained-Glass/"
            target="_blank"
            rel="noopener noreferrer"
            className="text-blue-600 underline"
          >
            Instructables
          </a>
        </p>
      </section>

      {/* Additional Resource */}
      <section className="mb-12">
        <h2 className="text-2xl font-semibold mb-3">Additional Learning Resource</h2>
        <p className="mb-2">
          For a comprehensive understanding, refer to this PDF guide on basic stained glass 
          making techniques:
        </p>
        <a
          href="https://www.anythinginstainedglass.com/books/LookInside/BasicStainedGlassMakingLookInsidetheBook.pdf"
          target="_blank"
          rel="noopener noreferrer"
          className="text-blue-600 font-medium underline"
        >
          Basic Stained Glass Making PDF
        </a>
        <p className="mt-2">
          This resource covers essential skills such as scoring, grinding, and soldering, 
          providing a solid foundation for beginners.
        </p>
      </section>

      <hr className="mt-10 mb-6" />
      <p className="text-center text-gray-500 text-sm">
        © {new Date().getFullYear()} Stained Glass Visual Guide
      </p>
    </div>
  );
}

---

