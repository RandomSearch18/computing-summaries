# Software development methodologies

Here's an overview of the various software development lifecycles/methods/models.

## Software development lifecycle (SDLC)

1. ❓ Feasibility
2. 📋 Requirements
3. 🔎 Analysis
4. 🖌️ Design
5. 🧑‍💻 Implementation
6. ☑️ Testing
7. 🚀 Deployment
8. 👍 Evaluation
9. 🔧 Maintenance

## Software development methodology overview

<table><tbody>
<tr>
<th colspan=1></th>
<th>🔢 Waterfall lifecycle</th>
<th>😵‍💫 Spiral model</th>
<th>🏃 Agile development</th>
<th>👥 Extreme programming</th>
<th>⚡ Rapid application development</th>
</tr>

<tr>
  <th rowspan=1>Unique feature</th>
  <td>Well-defined sequence</td><td>Risk-driven</td><td>Sprints 🏃</td><td>Pair programming</td><td>Focus groups</td>
</tr>
<tr>
  <th rowspan=1>Important notes</th>
  <td>Traditional</td><td>Just a guide. Uses other methodologies as appropriate.</td><td>Group of methodologies. Refinement of RAD.</td><td>Framework focusing on team values/culture</td><td>Iterates on prototypes (kinda basic tbh)</td>
</tr>
<tr>
  <th rowspan=1>Main focus</th>
  <td>Clear responsibilities</td><td>Risk analysis and management</td><td>Programming!</td><td>Teamwork, shared ownership</td><td>Usability of the program</td>
</tr>
<tr>
  <th rowspan=1>Iterative?</th>
  <td class=no /><td class=yes /><td class=yes /><td class=yes /><td class=yes />
</tr>
<tr>
  <th rowspan=1>Prototypes?</th>
  <td class=no /><td class=yes /><td class=yes /><td class=yes /><td class=yes />
</tr>
<tr>
  <th rowspan=1>User involvement</th>
  <td class="no text">Minimal</td><td class=maybe>Frequent</td><td class="yes text">Constant</td><td class="yes text">Constant</td><td class=maybe>Frequent</td>
</tr>
<tr>
  <th rowspan=1>Handling changed requirements</th>
  <td class="no text">Terrible</td><td class="yes text">Good</td><td class="yes text">Very good</td><td class="yes text">Very good</td><td class="yes text">Good</td>
</tr>
<tr>
  <th rowspan=1>Good documentation?</th>
  <td class=yes /><td class=maybe>Maybe at the end</td><td class=no /><td class=maybe>Maybe</td><td class=no />
</tr>
<tr>
  <th rowspan=1>Risk analysis?</th>
  <td class=no /><td class=yes /><td class=no /><td class=no /><td class=no />
</tr>
<tr>
  <th rowspan=1>Focus groups?</th>
  <td class=no /><td class=no /><td class=no /><td class=no /><td class=yes />
</tr>
<tr>
  <th rowspan=1>Velocity</th>
  <td class="no text">Slow</td><td class="no text">Slow-ish</td><td class="maybe">Medium</td><td class="maybe">Medium</td><td class="yes text">Rapid!</td>
</tr>
</tbody></table>

## Sources

- Physics and Maths Tutor
  - [1.2.3 Software Development Intermediate notes](https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.2-Software-and-Software-Development/Intermediate/1.2.3.%20Software%20Development.pdf)
  - [1.2.3 Software Development Advanced notes](https://pmt.physicsandmathstutor.com/download/Computer-Science/A-level/Notes/OCR/1.2-Software-and-Software-Development/Advanced/1.2.3.%20Software%20Development.pdf)
- Craig'n'Dave
  - [1.2 Development methodologies part 1](https://www.youtube.com/watch?v=qEmrXu8d1ys)

<style>
td.yes {
  background-color: #00d13833 !important;
}
td.yes:not(.text)::after {
  content: "Yes";
}

td.no {
  background-color: #d1000033 !important;
}
td.no:not(.text)::after {
  content: "No";
}

td.maybe {
  background-color: #ffd70033 !important;
}

td.na {
  background-color: #62626240 !important;
}
td.na::after {
  content: "N/A";
}
</style>
