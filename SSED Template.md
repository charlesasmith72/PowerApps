Below is an HTML page that uses only inline styles on each element. Note that inline styles cannot define pseudo-classes (like :hover or :active) without a style block or external CSS, so this example only defines the default appearance.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flowbite Inline</title>
  </head>
  <body style="margin:0; font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; background-color:#f9fafb;">
    <!-- Top Navigation Bar -->
    <nav style="background-color:#fff; border-bottom:1px solid #e5e7eb; padding:0.75rem 1rem; display:flex; align-items:center; justify-content:space-between;">
      <h1 style="font-size:2.5rem; font-weight:bold; color:#1e40af;margin-top: 0px;margin-bottom: 0px">SSED Database</h1>
      <div>
        <a href="#" style="margin-right:1rem; font-size:1.5rem; color:#4b5563; text-decoration:none;">Home</a>
        <a href="#" style="margin-right:1rem; font-size:1.5rem; color:#4b5563; text-decoration:none;">Team</a>
        <a href="#" style="margin-right:1rem; font-size:1.5rem; color:#4b5563; text-decoration:none;">Records</a>
        <a href="#" style="font-size:1.5rem; color:#4b5563; text-decoration:none;">Settings</a>
      </div>
    </nav>

    <!-- Main Container with Sidebar and Content -->
    <div style="display:flex; min-height:calc(100vh - 75px);">
      <!-- Sidebar -->
      <aside style="width:250px; background-color:#fff; border-right:1px solid #e5e7eb; padding:1rem;">
        <ul style="list-style:none; padding:0; margin:0;">
          <!-- Request for AT (blue indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#3B82F6;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Request for AT</span>
            </a>
          </li>
          <!-- AT Concurrence (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">AT Concurrence</span>
            </a>
          </li>
          <!-- AT Orders (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">AT Orders</span>
            </a>
          </li>
          <!-- Help Desk Tickets (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Help Desk Tickets</span>
            </a>
          </li>
          <!-- Serial Numbers (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Serial Numbers</span>
            </a>
          </li>
          <!-- Query Menu (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Query Menu</span>
            </a>
          </li>
          <!-- Order Menu (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Order Menu</span>
            </a>
          </li>
          <!-- Menu List (50% lighter grey indicator) -->
          <li style="margin-bottom:1rem;">
            <a href="#" style="display:flex; align-items:center; padding:0.5rem; border-radius:0.375rem; color:#4b5563; text-decoration:none;">
              <span style="display:inline-block; width:8px; height:8px; border-radius:50%; background-color:#CED1D7;"></span>
              <span style="margin-left:0.75rem; font-size:1rem;">Menu List</span>
            </a>
          </li>
        </ul>
      </aside>

      <!-- Main Content Area -->
      <main style="flex-grow:1; padding:2rem; text-align:center; color:#111827;">
        <h1 style="font-size:2.25rem; font-weight:600;">Flowbite Inline</h1>
      </main>
    </div>
  </body>
</html>

```

> **Note:**  
> Inline styles apply only to the element’s default state. CSS pseudo-classes like `:hover` or `:active` (which normally enable effects on mouseover or click) cannot be defined with inline styles alone. To achieve such effects, a `<style>` tag or external CSS is required.
