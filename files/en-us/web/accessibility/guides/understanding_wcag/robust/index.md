---
title: Robust
slug: Web/Accessibility/Guides/Understanding_WCAG/Robust
page-type: guide
sidebar: accessibilitysidebar
---

This article provides practical advice on how to write your web content so that it conforms to the success criteria outlined in the **Robust** principle of the Web Content Accessibility Guidelines (WCAG) 2.0 and 2.1. Robust states that content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies. This can generally be achieved by following web standards and [testing rigorously](/en-US/docs/Learn_web_development/Extensions/Testing).

> [!NOTE]
> To read the W3C definitions for Robust and its guidelines and success criteria, see [Principle 4: Robust — Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies.](https://w3c.github.io/wcag/guidelines/22/#robust)

## Guideline 4.1 — Compatible: Maximize compatibility with current and future user agents, including assistive technologies

This guideline focuses on making content as compatible as possible, not only with current user agents (e.g., browsers), but also with future ones too.

<table class="standard-table">
  <thead>
    <tr>
      <th scope="col">Success criteria</th>
      <th scope="col">How to conform to the criteria</th>
      <th scope="col">Practical resource</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>4.1.1 Parsing (A)</td>
      <td>
        <p>
          Content should be well-formed so it can be parsed successfully by
          browsers and other user agents such as screen readers.
        </p>
        <p>
          To pass this criterion, make sure that your HTML is as valid as
          possible. Use the
          <a href="https://validator.w3.org/">W3C validator</a> to validate your
          markup.
        </p>
      </td>
      <td>
        See
        <a href="/en-US/docs/Learn_web_development/Core/Structuring_content/Debugging_HTML"
          >Debugging HTML</a
        >
        for a practical guide.
      </td>
    </tr>
    <tr>
      <td>4.1.2 Name, Role, Value (A)</td>
      <td>
        <p>
          The name and role of user interface components (e.g., form inputs,
          buttons, links, etc.) should be programmatically determinable.
        </p>
        <p>
          When using semantic elements correctly for their intended purpose,
          this criterion should be passed automatically. When scripting custom
          components, you will need to use WAI-ARIA roles and other features to
          make sure your controls will be interpreted and are able to be used as
          intended, e.g., not only by sighted mouse users, but also by
          screen reader users, keyboard-only users, etc.
        </p>
      </td>
      <td>
        See
        <a href="/en-US/docs/Learn_web_development/Core/Accessibility/HTML"
          >HTML: A good basis for accessibility</a
        >
        and
        <a href="/en-US/docs/Learn_web_development/Core/Accessibility/WAI-ARIA_basics"
          >WAI-ARIA basics</a
        >.
      </td>
    </tr>
    <tr>
      <td>
        4.1.3 Status Messages (AA)
      </td>
      <td>
        <p>
          Assistive technology users are made aware of new status messages added
          to the page.
        </p>
      </td>
      <td>
        <a
          href="https://www.w3.org/WAI/WCAG21/Understanding/status-messages.html"
          >Understanding Status Messages</a
        >
      </td>
    </tr>
  </tbody>
</table>

> [!NOTE]
> Also see the WCAG description for [Guideline 4.1: Compatible: Maximize compatibility with current and future user agents, including assistive technologies.](https://w3c.github.io/wcag/guidelines/22/#compatible)

## See also

- [WCAG](/en-US/docs/Web/Accessibility/Guides/Understanding_WCAG)
  1. [Perceivable](/en-US/docs/Web/Accessibility/Guides/Understanding_WCAG/Perceivable)
  2. [Operable](/en-US/docs/Web/Accessibility/Guides/Understanding_WCAG/Operable)
  3. [Understandable](/en-US/docs/Web/Accessibility/Guides/Understanding_WCAG/Understandable)
  4. Robust
