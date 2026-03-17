<div style="display: flex; justify-content: space-between; align-items: center; padding: 12px 0; border-top: 1px solid #eee; border-bottom: 1px solid #eee; margin: 20px 0; color: #555; font-size: 0.9em;">
  <span><strong>ID:</strong> {{ page.meta.id }}</span>
  <span><strong>Version:</strong> {{ page.meta.version }}</span>
  <span><strong>Status:</strong> 
    <span class="status-tag status-{{ page.meta.status | lower }}">
      {{ page.meta.status }}
    </span>
  </span>
  <span><strong>Maj:</strong> {{ page.meta.updated }}</span>
</div>
