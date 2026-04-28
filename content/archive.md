# 归档

<div class="archive-page">
  <div class="archive-header">
    <h1 class="archive-title">归档</h1>
    <p class="archive-count">共 10 篇文章</p>
  </div>

  <div class="archive-content">
    <div class="year-section">
      <div class="year-header">
        <h2 class="year-title">2025</h2>
        <span class="year-post-count">10 篇</span>
      </div>
      <div class="post-list">
        <div class="post-item">
          <span class="post-date">12-01</span>
          <a href="/posts/test-post-1.html" class="post-title">测试文章 1</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-02</span>
          <a href="/posts/test-post-2.html" class="post-title">测试文章 2</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-03</span>
          <a href="/posts/test-post-3.html" class="post-title">测试文章 3</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-04</span>
          <a href="/posts/test-post-4.html" class="post-title">测试文章 4</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-05</span>
          <a href="/posts/test-post-5.html" class="post-title">测试文章 5</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-06</span>
          <a href="/posts/test-post-6.html" class="post-title">测试文章 6</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-07</span>
          <a href="/posts/test-post-7.html" class="post-title">测试文章 7</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-08</span>
          <a href="/posts/test-post-8.html" class="post-title">测试文章 8</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-09</span>
          <a href="/posts/test-post-9.html" class="post-title">测试文章 9</a>
        </div>
        <div class="post-item">
          <span class="post-date">12-10</span>
          <a href="/posts/test-post-10.html" class="post-title">测试文章 10</a>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
.archive-page {
  max-width: 800px;
  margin: 0 auto;
  padding: 3rem 20px 4rem;
}

.archive-header {
  text-align: center;
  margin-bottom: 3rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid var(--border-color);
}

.archive-title {
  font-size: 2.5rem;
  font-weight: 700;
  color: var(--title-color);
  margin-bottom: 0.5rem;
}

.archive-count {
  font-size: 1rem;
  color: var(--desc-color);
  margin: 0;
}

.archive-content {
  margin-top: 2rem;
}

.year-section {
  margin-bottom: 3rem;
}

.year-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--border-color);
}

.year-title {
  font-size: 1.8rem;
  font-weight: 700;
  color: var(--title-color);
  margin: 0;
}

.year-post-count {
  font-size: 1rem;
  color: var(--desc-color);
  background: var(--card-bg);
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
}

.post-list {
  margin-left: 0;
  padding-left: 0;
}

.post-item {
  display: flex;
  align-items: center;
  padding: 0.75rem 0;
  border-bottom: 1px dashed var(--border-color);
  transition: all 0.2s ease;
}

.post-item:last-child {
  border-bottom: none;
}

.post-item:hover {
  padding-left: 0.5rem;
}

.post-item:hover .post-title {
  color: var(--theme-color);
}

.post-date {
  font-size: 0.9rem;
  color: var(--desc-color);
  min-width: 60px;
  margin-right: 1.5rem;
  font-family: monospace;
}

.post-title {
  text-decoration: none;
  color: var(--title-color);
  font-size: 1rem;
  transition: color 0.2s ease;
  flex: 1;
}

@media (max-width: 768px) {
  .archive-page {
    padding: 2rem 15px 3rem;
  }
  
  .archive-title {
    font-size: 2rem;
  }
  
  .year-title {
    font-size: 1.5rem;
  }
  
  .post-date {
    min-width: 50px;
    margin-right: 1rem;
  }
  
  .post-title {
    font-size: 0.9rem;
  }
}
</style>
