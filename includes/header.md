<div style="display: flex; justify-content: space-between; align-items: center; padding: 12px 0; border-top: 1px solid #eee; border-bottom: 1px solid #eee; margin: 20px 0; color: #555; font-size: 0.9em;">
  <span><strong>ID:</strong> {{ metadata.id }}</span>
  <span><strong>Version:</strong> {{ metadata.version }}</span>
  <span><strong>Status:</strong> 
    <span class="status-tag status-{{ metadata.status | lower }}">
      {{ metadata.status }}
    </span>
  </span>
  <span><strong>Maj:</strong> {{ metadata.updated }}</span>
</div>
