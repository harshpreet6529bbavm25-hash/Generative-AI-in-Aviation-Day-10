# Generative-AI-in-Aviation-Day-10
Day 10 lab exploring AI image generation, five-part prompt engineering, iterative refinement, prompt bleed, aviation accuracy, professionalism audits, ethical AI use, and responsible image generation for aviation communication.
# DAY 10 — LAB 10
# Image Generation: Five-Part Prompt and Iterative Refinement

## Student Information

**Name:** Harshpreet Kaur  
**Program:** BBA Aviation Management  
**Lab:** Day 10 — Lab 10  
**Topic:** Image Generation: Five-Part Prompt and Iterative Refinement  
**Repository:** genai-business-portfolio  
**Folder:** day-10-image-generation  

---

# 1. Objective

The objective of this lab is to understand how structured prompting can improve AI-generated aviation visuals.

The activity focuses on:

- Five-part image prompting
- Subject specification
- Style and medium
- Environment
- Lighting
- Aspect ratio
- Iterative refinement
- Prompt bleed
- Aviation accuracy
- Professionalism
- Ethical and responsible AI image generation
- Human review before publication

---

# 2. Weak Prompt

## Prompt Used

"Create an airport image."

## Diagnosis of the Weak Prompt

| Prompt Component | Present or Missing? | What Should Be Added? |
|---|---|---|
| Subject | Missing | Specify passengers, kiosks, aircraft, staff, etc. |
| Style | Missing | Specify photorealistic, corporate photography, illustration, etc. |
| Environment | Partially present | Specify a modern international airport terminal or check-in area. |
| Lighting | Missing | Specify natural daylight or professional lighting. |
| Aspect ratio | Missing | Specify 16:9 for a presentation. |
| Intended use | Missing | State that the image is for a business presentation. |
| Brand restrictions | Missing | Exclude airline logos, airport names and trademarks. |
| Text restrictions | Missing | Exclude readable promotional text and personal information. |
| Accuracy instructions | Missing | Request realistic airport equipment, passenger movement and aviation details. |

## Observation

The weak prompt provides very little direction to the image-generation model.

As a result, the generated image may vary significantly in subject, composition, airport design, lighting and realism.

---

# 3. Five-Part Image Prompt

The five main components used are:

1. Subject
2. Medium or style
3. Environment
4. Lighting
5. Aspect ratio

## Structured Prompt

| Image-Prompt Component | Student Response |
|---|---|
| Subject | Diverse young adult travellers using self-service check-in kiosks |
| Medium or style | Professional photorealistic corporate photography |
| Environment | Modern international airport terminal with realistic travel bags and passenger movement |
| Lighting | Bright natural daylight with clean professional illumination |
| Aspect ratio | 16:9 landscape for a business presentation |

## Final Structured Prompt

> Create a professional, photorealistic image of a diverse group of young adult travellers using self-service check-in kiosks inside a modern international airport terminal. Show a clean, spacious environment with realistic travel bags and clear passenger movement. Use bright natural daylight and a neutral blue-and-white colour palette. Use a 16:9 landscape aspect ratio suitable for a business presentation. Do not include airline logos, airport names, readable personal information, boarding-pass details or promotional text.

---

# 4. Weak Prompt vs Structured Prompt

| Evaluation Criterion | Weak Prompt Image | Structured Prompt Image |
|---|---|---|
| Clear subject | Partially clear | Clearly shows young travellers using kiosks |
| Appropriate aviation setting | General airport setting | Clearly specified modern international terminal |
| Professional style | Not specified; may vary | Photorealistic and professional |
| Suitable lighting | Not specified | Bright natural/professional lighting |
| Correct aspect ratio | Not specified | 16:9 landscape |
| Realistic details | May contain unrealistic details | More controlled and realistic aviation environment |
| Unwanted logos or text | May appear | Explicitly restricted |
| Suitable for presentation use | Limited | More suitable for a business presentation |

## Conclusion

The structured prompt produced a more useful image because it clearly defined the subject, visual style, environment, lighting and aspect ratio.

The environment and subject specifications made the biggest difference because they provided the image-generation tool with a clear aviation scenario instead of simply asking for an airport image.

The weak prompt could produce unwanted elements such as random signage, unrealistic airport equipment, logos or distorted text.

Even if the structured image looks professional, it should still be reviewed before publication because AI-generated images can contain inaccurate details, distorted people, incorrect technology or unreadable text.

Therefore, the structured image is suitable as a presentation draft, but human review is still required before publishing or using it for official aviation communication.

---

# 5. Iterative Refinement

## Refinement Table

| Version | Variable Changed | Expected Effect | Actual Effect | Unexpected Changes |
|---|---|---|---|---|
| Original | None | Establish a baseline photorealistic airport self-service check-in image in 16:9 format with bright natural daylight. | Produced a realistic, spacious airport terminal with diverse young travellers using self-service kiosks, luggage and aircraft visible in the background. | Some small screen/signage details appeared readable or semi-readable despite text restrictions. |
| Version 1 | Style | Replace photorealism with a clean flat-vector illustration while keeping the subject, environment, lighting and composition broadly similar. | Image changed to a clean illustrated/vector appearance with simplified people, kiosks and airport architecture. | More stylized colours, simplified facial features and additional graphic-style airport signage appeared. |
| Version 2 | Lighting | Replace bright natural daylight with warm evening lighting while maintaining the photorealistic airport check-in scene. | Terminal became warmer and more cinematic, with sunset light, orange tones and stronger floor reflections. | Overall mood changed significantly and the background became more sunset-focused. |
| Version 3 | Aspect ratio | Change composition from 16:9 landscape to 1:1 square format suitable for social media. | Scene was reframed into a square composition while retaining the airport, travellers, kiosks and photorealistic style. | Some elements were repositioned or cropped, and warm-looking light remained despite the daylight instruction. |
| Version 4 | Environment | Replace the self-service check-in area with a boarding-gate waiting area while retaining the other major visual instructions. | Scene changed to a boarding-gate lounge with passengers sitting and waiting, carry-on luggage, gate seating and an aircraft near a jet bridge. | AI introduced specific gate information such as "Gate B12", flight times, "On Time" and promotional-style wall text. |

## Key Observation

The iterative process shows that changing one variable at a time makes it easier to observe the effect of each prompt modification.

However, the results also demonstrate **prompt bleed**.

Changing one instruction does not guarantee that every other visual element will remain identical.

The most noticeable example is Version 4, where changing the environment caused the model to introduce specific gate numbers, flight times and other text that were not requested.

## Conclusion

Controlled single-variable refinement improves prompt testing, but every generated image still requires human inspection for:

- Unwanted text
- Inaccurate aviation details
- Visual consistency
- Professionalism

---

# 6. Prompt Bleed

Prompt bleed occurs when an instruction unintentionally affects other parts of the image or when elements from one instruction appear in an unwanted location.

## Prompt-Bleed Analysis

| Prompt Instruction | Intended Result | Unwanted Result | Corrective Instruction |
|---|---|---|---|
| Neutral blue-and-white colour palette | Consistent blue-and-white airport visual | Some versions introduced warmer colours | Maintain a neutral blue-and-white palette and avoid additional dominant colours. |
| No readable promotional text | Clean image without artificial text | Version 4 introduced readable gate information and wall text | Remove all readable text, flight numbers, gate numbers and promotional messages. Keep displays blank. |
| Realistic aviation environment | Realistic airport equipment and operations | Some screens contained artificial or unclear interface details | Use realistic airport equipment but keep all digital screens blank or non-readable. |
| Boarding-gate waiting area | Passengers waiting comfortably at an airport gate | Model added specific operational information and signage | Show a generic boarding-gate waiting area without real or invented operational information. |

---

# 7. Correcting Unwanted Elements

## Correction Prompt

> Remove all readable gate numbers, flight times, flight-status information, promotional messages and other artificial text. Keep the boarding-gate waiting area, passengers, luggage, aircraft and airport architecture unchanged. Keep the aircraft only outside the terminal windows. Maintain realistic passenger spacing and unobstructed walkways. Do not add airline logos, airport names, personal information or operational information. Keep digital displays blank or non-readable.

This targeted correction focuses on removing misleading text while preserving the main aviation scene.

---

# 8. Aviation Accuracy Audit

| Accuracy Check | Acceptable? | Problem Identified | Required Correction |
|---|---|---|---|
| Aircraft structure appears realistic | Yes, mostly | Aircraft is generally recognizable and realistic | Minor visual inspection still required |
| Aircraft is located appropriately | Yes | Aircraft is shown outside the terminal through the windows | Keep aircraft outside the terminal |
| Passenger behaviour appears realistic | Yes | Passengers are seated, waiting and using normal travel equipment | No major correction required |
| Airport equipment appears usable | Yes, mostly | Kiosks and airport seating appear plausible | Review equipment details before publication |
| Walkways and exits are unobstructed | Yes | Main passenger movement areas remain reasonably clear | Maintain clear walkways |
| Signs are accurate or intentionally blank | No | Version 4 introduced invented gate and flight information | Remove readable operational information |
| Uniforms do not misuse real branding | Yes | No obvious real airline uniform branding is required | Continue avoiding airline branding |
| No personal information is visible | Yes | No obvious passenger personal information is visible | Keep screens and documents non-readable |
| No unsafe activity is shown | Yes | Passengers are behaving normally | No major correction required |
| No misleading operational information appears | No | Version 4 displayed invented gate/flight information | Remove all fake operational details |

---

# 9. Professionalism Audit

| Professionalism Criterion | Score | Comments |
|---|---:|---|
| Visual quality | 5/5 | High-quality and visually detailed airport environment |
| Business relevance | 5/5 | Directly relevant to aviation, passenger experience and airport technology |
| Composition | 5/5 | Clear foreground subject and supporting airport environment |
| Colour consistency | 4/5 | Generally consistent, although lighting changes affected colour balance |
| Readability | 3/5 | Artificial text and airport displays create some concerns |
| Audience suitability | 5/5 | Suitable for a BBA Aviation Management presentation after correction |
| Brand neutrality | 5/5 | No intentional real airline branding |
| Overall professionalism | 4/5 | Strong visual quality, but human review and text correction are required |

## Overall Observation

The image has strong presentation value, but it should not be treated as an authentic operational airport photograph because AI-generated text and operational details can be inaccurate.

---

# 10. Three Aviation Visuals

## Visual A — Airline Marketing

### Business Purpose

Create an attractive campaign visual encouraging students to explore domestic destinations.

### Target Audience

Young adults and university students interested in travel.

### Five-Part Prompt

**Subject:** Young adult travellers preparing for a domestic journey  
**Style:** Professional photorealistic commercial photography  
**Environment:** Modern Indian airport terminal with domestic-travel atmosphere  
**Lighting:** Bright natural daylight  
**Aspect ratio:** 16:9 landscape  

### Complete Prompt

> Create a professional photorealistic image of diverse young adult travellers preparing for a domestic journey inside a modern airport terminal. Show travel bags, a clean check-in environment and an energetic but realistic passenger atmosphere. Use bright natural daylight and a professional blue-and-white colour palette. Use a 16:9 landscape composition suitable for an aviation marketing presentation. Do not include real airline logos, airline names, ticket prices, discount claims, airport names, personal information or readable promotional text.

### Problems to Check

- Unwanted airline logos
- Fake ticket prices
- Unreadable or incorrect promotional text
- Unrealistic aircraft or airport details

### Revised Prompt

> Keep the same scene but remove all logos, airline names, prices and promotional text. Keep the visual generic and brand-neutral.

---

# 11. Visual B — Airport Awareness

### Business Purpose

Encourage passengers to keep airport terminal walkways clear.

### Target Audience

Airport passengers and travellers.

### Five-Part Prompt

**Subject:** Passengers maintaining clear terminal walkways  
**Style:** Clean professional photorealistic photography  
**Environment:** Modern airport terminal concourse  
**Lighting:** Bright neutral lighting  
**Aspect ratio:** 16:9 landscape  

### Complete Prompt

> Create a professional photorealistic image of passengers moving responsibly through a modern airport terminal while keeping the main walkways clear. Show travellers standing to the side with their luggage rather than blocking passenger movement. Include realistic airport seating and terminal infrastructure. Use bright neutral lighting and a clean blue-and-white colour palette. Use a 16:9 landscape format. Do not include airline logos, airport names, personal information or inaccurate safety signage.

### Problems to Check

- Bags blocking walkways
- Crowded or unsafe passenger movement
- Incorrect emergency-exit signs
- Unnecessary text

### Revised Prompt

> Maintain realistic passenger spacing, keep all walkways and emergency exits unobstructed, remove inaccurate signage and keep all displays blank.

---

# 12. Visual C — Aviation Presentation

## Presentation Title

**Improving Passenger Experience Through Airport Technology**

### Business Purpose

Provide a professional presentation visual explaining the role of airport self-service technology.

### Target Audience

Students, teachers and aviation-management audiences.

### Five-Part Prompt

**Subject:** Passengers using airport self-service technology  
**Style:** Professional photorealistic corporate photography  
**Environment:** Modern international airport terminal  
**Lighting:** Bright natural daylight  
**Aspect ratio:** 16:9 landscape  

### Complete Prompt

> Create a professional photorealistic presentation image showing diverse young adult travellers using realistic self-service check-in technology inside a modern international airport terminal. Show clean kiosks, realistic luggage, clear passenger movement and a spacious terminal environment. Use bright natural daylight and a neutral blue-and-white colour palette. Use a 16:9 landscape composition suitable for a professional business presentation. Do not include airline logos, airport names, passenger data, boarding-pass details, fake charts, statistics or readable promotional text.

### Problems to Check

- Fake statistics
- Fake charts
- Unreadable text
- Incorrect kiosk design
- Personal information
- Airline branding

### Revised Prompt

> Remove all charts, statistics, logos and readable text. Keep the technology realistic and leave all digital screens blank or non-readable.

---

# 13. Image-Generation Limitations

| Question | Answer |
|---|---|
| Did the tool create readable text? | Yes. Some generated airport signs contained readable or semi-readable text, particularly Version 4. |
| Were hands and faces realistic? | Mostly yes. The people were generally realistic, although AI-generated human details should still be inspected closely. |
| Were aircraft and airport structures realistic? | Mostly yes. The airport environment and aircraft were visually convincing, but operational accuracy cannot be assumed from appearance alone. |
| Did the image contain unwanted logos? | No obvious real airline logo was intentionally included, but this should always be checked. |
| Did it introduce cultural or demographic stereotypes? | No obvious stereotype was identified in the generated versions reviewed. |
| Did it follow the requested aspect ratio? | Yes. Version 3 was changed to a square 1:1 format as requested. |
| Did it include elements that were not requested? | Yes. Version 4 introduced gate numbers, flight times, status information and wall text. |
| Could the image mislead viewers? | Yes. Fake operational information could make viewers believe that the image represents a real airport or flight. |
| Should AI-use disclosure be added? | Yes, when required by the context, institution or platform. |
| What human corrections would be required? | Remove fake text, verify aviation details, check aircraft placement, inspect people/equipment and confirm that no branding or personal information is present. |

---

# 14. Ethical and Responsible-Use Check

| Check | Response |
|---|---|
| Is the image deceptive? | It could become deceptive if presented as an authentic photograph of a real airport or event. |
| Does it imitate a real airline or airport without permission? | The prompts were designed to avoid real airline and airport branding. |
| Does it include unauthorised logos? | No intentional real logos were requested; final images should still be checked. |
| Does it misrepresent a real event? | It could if the generated scene were presented as documentation of an actual event. |
| Does it depict a real individual without consent? | The images use AI-generated people rather than intentionally depicting a named real individual. |
| Does it reinforce stereotypes? | No obvious stereotype was identified in the reviewed images. |
| Does it contain false safety information? | Version 4 contained invented operational information, so it requires correction. |
| Could viewers mistake it for an authentic operational photograph? | Yes, particularly because the photorealistic versions look like real airport photography. |
| Are usage rights understood? | The intended use and applicable tool/platform terms should be checked before commercial publication. |
| Is AI-use disclosure required? | Disclosure should be made when required by the institution, platform or applicable rules. |

---

# 15. Peer Review

Since actual classmate feedback has not been provided, this section is a self-review based on the generated Version 4 image.

**Important:** Replace this with actual peer feedback if the instructor requires evidence of peer review.

| Review Question | Result | Suggested Improvement |
|---|---|---|
| Is the subject clear? | Yes | Keep passengers and airport environment clearly visible. |
| Is the style appropriate? | Yes | Photorealistic style is suitable for a professional aviation presentation. |
| Is the environment realistic? | Yes, mostly | Verify airport equipment and aircraft details. |
| Is the lighting suitable? | Yes | Maintain consistent natural lighting where required. |
| Is the aspect ratio appropriate? | Yes | Select the ratio according to intended use. |
| Are there unwanted elements? | Yes | Remove invented gate, flight and promotional text. |
| Are there aviation inaccuracies? | Potentially | Conduct a detailed operational review before publication. |
| Is the image professional? | Yes, after correction | Remove artificial text and misleading information. |
| Is the image ethical and responsible? | Yes, after correction | Do not present it as an authentic operational photograph. |
| Is further human review required? | Yes | Human review is necessary before final publication. |

---

# 16. Student Reflection

## 1. What are the five parts of an effective image prompt?

The five parts are:

1. Subject
2. Medium or style
3. Environment
4. Lighting
5. Aspect ratio

These components provide the image-generation tool with clearer instructions about what to create and how the final image should look.

## 2. What is the difference between image generation and image retrieval?

Image retrieval finds an existing image from a source, while image generation creates a new image based on a text prompt.

## 3. Why should only one variable be changed at a time?

Changing one variable at a time makes it easier to identify which instruction caused a particular visual change.

It also makes the refinement process more controlled.

## 4. What is prompt bleed?

Prompt bleed occurs when an instruction unintentionally affects another part of the generated image or causes an unwanted element to appear.

## 5. Give one example of an aviation inaccuracy found in an AI-generated image.

One example was the introduction of invented gate and flight information, such as "Gate B12", a departure time and an "On Time" status, even though no operational information was requested.

## 6. Why should text normally be added separately in a design tool?

AI image-generation tools can produce distorted, incorrect or meaningless text.

Adding text separately in a tool such as Canva provides better control over spelling, formatting and accuracy.

## 7. Why should real airline logos be avoided?

Real airline logos can create brand, trademark and authenticity concerns.

A generic aviation visual is safer when a real brand is not required.

## 8. How did peer feedback improve your image?

Peer review can identify visual problems that the creator may overlook, such as fake text, unrealistic airport details, poor composition or misleading information.

The feedback can then be used to refine the image.

## 9. What ethical concerns apply to AI-generated aviation visuals?

Important concerns include:

- Misleading viewers
- Fake operational information
- Unauthorised branding
- Privacy
- Stereotypes
- Inaccurate safety information
- Authenticity
- Appropriate AI disclosure

## 10. Why must an AI-generated image be reviewed before publication?

AI-generated images can contain realistic-looking but incorrect people, equipment, aircraft, signs, text or operational details.

Human review helps identify and correct these problems before the image is used publicly.

---

# 17. AI Usage Declaration

An AI image-generation tool was used to create the visuals in this activity.

I independently designed and refined the prompts, checked the images for accuracy, professionalism, bias and responsible use, and completed the reflection.

AI-generated outputs were reviewed rather than being treated as automatically correct.

---

# 18. Final Learning

The Day 10 lab demonstrates that effective AI image generation requires more than writing a simple prompt.

A structured five-part prompt provides greater control over:

- Subject
- Style
- Environment
- Lighting
- Aspect ratio

Iterative refinement allows one variable to be tested at a time.

However, prompt bleed can still occur, meaning that changing one instruction may unintentionally change other parts of the image.

Therefore, every AI-generated aviation visual should undergo:

1. Prompt review
2. Visual inspection
3. Aviation accuracy audit
4. Professionalism audit
5. Ethical-use review
6. Human review before publication

The main lesson is:

> AI-generated aviation visuals can look realistic without being operationally accurate.

---

# 19. GitHub Submission

**Repository:**
`genai-business-portfolio`

**Folder:**
`day-10-image-generation`

**Markdown file:**
`aviation-image-generation.md`

**Images folder:**
`images/`

## Required Images

- `weak-prompt.png`
- `structured-prompt.png`
- `version-1-style.png`
- `version-2-lighting.png`
- `version-3-aspect-ratio.png`
- `version-4-environment.png`
- `corrected-image.png`
- `visual-a-airline-marketing.png`
- `visual-b-airport-awareness.png`
- `visual-c-aviation-presentation.png`

## Commit Message

`Add Day 10 Lab 10 - Aviation Image Generation`

## GitHub Link

[PASTE YOUR ACTUAL GITHUB FILE LINK HERE]

---

# 20. Final Assessment Checklist

| Assessment Criterion | Status |
|---|---|
| Applied all five image-prompt components | Yes |
| Changed one variable at a time | Yes |
| Identified prompt bleed | Yes |
| Corrected unwanted elements | Yes — correction prompt prepared |
| Checked aviation accuracy | Yes |
| Evaluated professionalism | Yes |
| Avoided unauthorised logos and personal data | Yes |
| Completed the ethical-use check | Yes |
| Revised the image after peer review | Pending actual peer feedback |
| Uploaded the activity and images to GitHub | Pending upload |

---

# Conclusion

The Day 10 lab demonstrates how structured prompt engineering and iterative refinement can improve AI-generated aviation visuals.

The five-part prompt provides clearer control over the generated image, while single-variable refinement makes it easier to understand the effect of individual prompt changes.

However, AI-generated images may still introduce:

- Fake text
- Incorrect operational information
- Unrealistic aviation details
- Branding
- Misleading visual information

Therefore, human inspection and responsible-use checks are essential before publication.

AI can assist with creating aviation visuals, but the final visual must be reviewed for accuracy, professionalism and authenticity.
