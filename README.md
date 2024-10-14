<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 align="center" tabindex="-1" class="heading-element" dir="auto" _msttexthash="10640461" _msthash="292">SQL页面</h1><a id="user-content-sqlpage" class="anchor" aria-label="永久链接：
SQL页面" href="#sqlpage" _mstaria-label="318032" _msthash="293"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><animated-image data-catalyst=""><a href="https://github.com/sqlpage/SQLPage/blob/main/docs/sqlpage.mp4" data-target="animated-image.originalLink"><img src="https://github.com/sqlpage/SQLPage/raw/main/docs/sqlpage.gif" alt="解释 sqlpage 概念的短视频" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage" _mstalt="1472055" _msthash="294"></a>
      
<p dir="auto" _msttexthash="1363687520" _msthash="299"><a href="https://sql.datapage.app" rel="nofollow" _istranslated="1">SQLpage</a> 是一个仅限 <strong _istranslated="1">SQL</strong> 的 Web 应用程序构建器。
它适用于数据科学家、分析师和商业智能团队
要快速构建强大的以数据为中心的应用程序，
无需担心任何传统的 Web 编程语言和概念。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="1171864668" _msthash="300">使用 SQLPage，您可以编写包含数据库查询的简单文件
选择、分组、更新、插入和删除您的数据，您将获得美观干净的网页
将数据显示为文本、列表、网格、绘图和表单。</font><code>.sql</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4284137" _msthash="301">例子</h2><a id="user-content-examples" class="anchor" aria-label="永久链接：示例" href="#examples" _mstaria-label="369876" _msthash="302"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr><td _msttexthash="4704375" _msthash="303">法典</td><td _msttexthash="5712993" _msthash="304">结果</td></tr>
</thead>
<tbody>
<tr>
<td>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">SELECT</span> 
    <span class="pl-s"><span class="pl-pds">'</span>list<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component,
    <span class="pl-s"><span class="pl-pds">'</span>Popular websites<span class="pl-pds">'</span></span> <span class="pl-k">as</span> title;
<span class="pl-k">SELECT</span> 
    name <span class="pl-k">as</span> title,
    url <span class="pl-k">as</span> link,
    CASE type
      WHEN <span class="pl-c1">1</span> THEN <span class="pl-s"><span class="pl-pds">'</span>blue<span class="pl-pds">'</span></span>
      ELSE <span class="pl-s"><span class="pl-pds">'</span>red<span class="pl-pds">'</span></span>
    END <span class="pl-k">as</span> color,
    description, icon, active
<span class="pl-k">FROM</span> website;</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SELECT 
    'list' as component,
    'Popular websites' as title;
SELECT 
    name as title,
    url as link,
    CASE type
      WHEN 1 THEN 'blue'
      ELSE 'red'
    END as color,
    description, icon, active
FROM website;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td><td>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sqlpage/SQLPage/blob/main/docs/demo-list.png"><img src="/sqlpage/SQLPage/raw/main/docs/demo-list.png" alt="SQLPage 列表组件" style="max-width: 100%;" _mstalt="452569" _msthash="305"></a></p>
</td></tr>
<tr>
<td>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">SELECT</span>
  <span class="pl-s"><span class="pl-pds">'</span>chart<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component,
  <span class="pl-s"><span class="pl-pds">'</span>Quarterly Revenue<span class="pl-pds">'</span></span> <span class="pl-k">as</span> title,
  <span class="pl-s"><span class="pl-pds">'</span>area<span class="pl-pds">'</span></span> <span class="pl-k">as</span> type;

<span class="pl-k">SELECT</span>
    quarter <span class="pl-k">AS</span> x,
    <span class="pl-c1">SUM</span>(revenue) <span class="pl-k">AS</span> y
<span class="pl-k">FROM</span> finances
<span class="pl-k">GROUP BY</span> quarter</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SELECT
  'chart' as component,
  'Quarterly Revenue' as title,
  'area' as type;

SELECT
    quarter AS x,
    SUM(revenue) AS y
FROM finances
GROUP BY quarter" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td><td>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sqlpage/SQLPage/blob/main/docs/demo-graph.png"><img src="/sqlpage/SQLPage/raw/main/docs/demo-graph.png" alt="SQLPage 列表组件" style="max-width: 100%;" _mstalt="452569" _msthash="306"></a></p>
</td></tr>
<tr>
<td>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">SELECT</span>
    <span class="pl-s"><span class="pl-pds">'</span>form<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component,
    <span class="pl-s"><span class="pl-pds">'</span>User<span class="pl-pds">'</span></span> <span class="pl-k">as</span> title,
    <span class="pl-s"><span class="pl-pds">'</span>Create new user<span class="pl-pds">'</span></span> <span class="pl-k">as</span> validate;

<span class="pl-k">SELECT</span>
    name, type, placeholder,
    required, description
<span class="pl-k">FROM</span> user_form;

<span class="pl-k">INSERT INTO</span> user
<span class="pl-k">SELECT</span> $first_name, $last_name, $birth_date
<span class="pl-k">WHERE</span> $first_name <span class="pl-k">IS NOT NULL</span>;</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="SELECT
    'form' as component,
    'User' as title,
    'Create new user' as validate;

SELECT
    name, type, placeholder,
    required, description
FROM user_form;

INSERT INTO user
SELECT $first_name, $last_name, $birth_date
WHERE $first_name IS NOT NULL;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td><td>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sqlpage/SQLPage/blob/main/docs/demo-form.png"><img src="/sqlpage/SQLPage/raw/main/docs/demo-form.png" alt="SQLPage 列表组件" style="max-width: 100%;" _mstalt="452569" _msthash="307"></a></p>
</td></tr>
<tr>
<td>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">select</span> <span class="pl-s"><span class="pl-pds">'</span>tab<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component, true <span class="pl-k">as</span> center;
<span class="pl-k">select</span> <span class="pl-s"><span class="pl-pds">'</span>Show all cards<span class="pl-pds">'</span></span> <span class="pl-k">as</span> title, <span class="pl-s"><span class="pl-pds">'</span>?<span class="pl-pds">'</span></span> <span class="pl-k">as</span> link,
  $tab is <span class="pl-k">null</span> <span class="pl-k">as</span> active;
<span class="pl-k">select</span>
  format(<span class="pl-s"><span class="pl-pds">'</span>Show %s cards<span class="pl-pds">'</span></span>, color) <span class="pl-k">as</span> title,
  format(<span class="pl-s"><span class="pl-pds">'</span>?tab=%s<span class="pl-pds">'</span></span>, color) <span class="pl-k">as</span> link,
  $tab<span class="pl-k">=</span>color <span class="pl-k">as</span> active
<span class="pl-k">from</span> tab_example_cards
<span class="pl-k">group by</span> color; 


<span class="pl-k">select</span> <span class="pl-s"><span class="pl-pds">'</span>card<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component;
<span class="pl-k">select</span>
  title, description, color
  image_url <span class="pl-k">as</span> top_image, link
<span class="pl-k">from</span> tab_example_cards
<span class="pl-k">where</span> $tab is <span class="pl-k">null</span> <span class="pl-k">or</span> $tab <span class="pl-k">=</span> color;

<span class="pl-k">select</span>
  <span class="pl-s"><span class="pl-pds">'</span>text<span class="pl-pds">'</span></span> <span class="pl-k">as</span> component,
  <span class="pl-c1">sqlpage</span>.<span class="pl-c1">read_file_as_text</span>(<span class="pl-s"><span class="pl-pds">'</span>footer.md<span class="pl-pds">'</span></span>) <span class="pl-k">as</span> contents_md</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="select 'tab' as component, true as center;
select 'Show all cards' as title, '?' as link,
  $tab is null as active;
select
  format('Show %s cards', color) as title,
  format('?tab=%s', color) as link,
  $tab=color as active
from tab_example_cards
group by color; 


select 'card' as component;
select
  title, description, color
  image_url as top_image, link
from tab_example_cards
where $tab is null or $tab = color;

select
  'text' as component,
  sqlpage.read_file_as_text('footer.md') as contents_md" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</td><td>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sqlpage/SQLPage/blob/main/docs/cards.png"><img src="/sqlpage/SQLPage/raw/main/docs/cards.png" alt="卡片组件 SQL 示例" style="max-width: 100%;" _mstalt="581295" _msthash="308"></a></p>
</td></tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="19335511" _msthash="309">支持的数据库</h2><a id="user-content-supported-databases" class="anchor" aria-label="永久链接：支持的数据库" href="#supported-databases" _mstaria-label="776763" _msthash="310"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="111312903" _msthash="311"><a href="https://www.sqlite.org/index.html" rel="nofollow" _istranslated="1">SQLite</a> 中，包括加载 <em _istranslated="1">Spatialite</em> 等<a href="/sqlpage/SQLPage/blob/main/configuration.md" _istranslated="1">扩展</a>的能力。</li>
<li _msttexthash="127749895" _msthash="312"><a href="https://www.postgresql.org/" rel="nofollow" _istranslated="1">PostgreSQL</a> 和其他兼容的数据库，例如 <em _istranslated="1">YugabyteDB</em>、<em _istranslated="1">CockroachDB</em> 和 <em _istranslated="1">Aurora</em>。</li>
<li _msttexthash="98023497" _msthash="313"><a href="https://www.mysql.com/" rel="nofollow" _istranslated="1">MySQL</a> 以及其他兼容的数据库，例如 <em _istranslated="1">MariaDB</em> 和 <em _istranslated="1">TiDB</em>。</li>
<li _msttexthash="236085278" _msthash="314"><a href="https://www.microsoft.com/en-us/sql-server" rel="nofollow" _istranslated="1">Microsoft SQL Server</a> 以及所有兼容的数据库和提供程序，例如 <em _istranslated="1">Azure SQL</em> 和 <em _istranslated="1">Amazon RDS</em>。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="10883795" _msthash="315">开始使用</h2><a id="user-content-get-started" class="anchor" aria-label="永久链接： 开始" href="#get-started" _mstaria-label="440895" _msthash="316"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="82855409" _msthash="317"><a href="https://sql.datapage.app/get_started.sql" rel="nofollow" _istranslated="1">阅读 SQLPage 网站上的官方<em _istranslated="1">入门</em>指南</a>。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="23220236" _msthash="318">使用可执行文件</h3><a id="user-content-using-executables" class="anchor" aria-label="永久链接：使用可执行文件" href="#using-executables" _mstaria-label="686686" _msthash="319"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="134400006" _msthash="320">最简单的入门方法是从 <a href="https://github.com/lovasoa/SQLpage/releases" _istranslated="1">releases 页面</a>下载最新版本。</p>
<ul dir="auto">
<li _msttexthash="206098217" _msthash="321">下载与您的操作系统（linux、macos 或 windows）对应的二进制文件。</li>
<li><font _mstmutation="1" _msttexthash="13077259" _msthash="322">解压：</font><code>tar -xzf sqlpage-*.tgz</code></li>
<li><font _mstmutation="1" _msttexthash="18209763" _msthash="323">运行它：</font><code>./sqlpage.bin</code></li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5065905" _msthash="324">使用 docker</h3><a id="user-content-with-docker" class="anchor" aria-label="永久链接：使用 docker" href="#with-docker" _mstaria-label="439582" _msthash="325"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="116154870" _msthash="326">要在服务器上运行，您可以使用 <a href="https://hub.docker.com/r/lovasoa/sqlpage" rel="nofollow" _istranslated="1">docker 镜像</a>：</p>
<ul dir="auto">
<li><a href="https://docs.docker.com/get-docker/" rel="nofollow" _msttexthash="5868551" _msthash="327">安装 docker</a></li>
<li><font _mstmutation="1" _msttexthash="50262680" _msthash="328">在终端中，执行以下命令。</font><ul dir="auto">
<li><code>docker run -it --name sqlpage -p 8080:8080 --volume "$(pwd):/var/www" --rm lovasoa/sqlpage</code></li>
<li>(<code>"$(pwd):/var/www"</code><font _mstmutation="1" _msttexthash="120367364" _msthash="329">允许 SQLPlayer 从当前工作目录运行 SQL 文件）</font></li>
</ul>
</li>
<li _msttexthash="94203603" _msthash="330">使用<a href="/sqlpage/SQLPage/blob/main/index.sql" _istranslated="1">此示例</a>中的内容创建一个名为 index.sql 的文件</li>
<li _msttexthash="23440729" _msthash="331">在浏览器中打开 <a href="https://localhost:8080" rel="nofollow" _istranslated="1">https://localhost:8080</a></li>
<li><font _mstmutation="1" _msttexthash="469481103" _msthash="332">可选地，你也可以挂载一个包含 sqlpage 配置文件
自定义组件和迁移
（请参阅 <a href="/sqlpage/SQLPage/blob/main/configuration.md" _mstmutation="1" _istranslated="1">configuration.md</a>）添加到容器中。</font><code>/etc/sqlpage</code><ul dir="auto">
<li><font _mstmutation="1" _msttexthash="42947879" _msthash="333">例如，您可以使用：</font><ul dir="auto">
<li><code>docker run -it --name sqlpage -p 8080:8080 --volume "$(pwd)/source:/var/www" --volume "$(pwd)/configuration:/etc/sqlpage:ro" --rm lovasoa/sqlpage</code></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="166720970" _msthash="334">并将您的网站放在名为 的文件夹中，将您的网站放在名为 .</font><code>source</code><code>sqlpage.json</code><code>configuration</code></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="1986450336" _msthash="335">如果您想构建自己的 docker 镜像，不建议将原始 sqlpage 镜像作为基础，因为它非常精简，并且可能不包含您需要的依赖项。相反，你可以以 debian 为基础，简单地将官方镜像中的 sqlpage 二进制文件复制到你自己的镜像中：</font><ul dir="auto">
<li>
<div class="highlight highlight-source-dockerfile notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">FROM</span> debian:stable-slim
<span class="pl-k">COPY</span> --from=lovasoa/sqlpage:main /usr/local/bin/sqlpage /usr/local/bin/sqlpage</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="FROM debian:stable-slim
COPY --from=lovasoa/sqlpage:main /usr/local/bin/sqlpage /usr/local/bin/sqlpage" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
</li>
</ul>
<p dir="auto" _msttexthash="1304827121" _msthash="336">我们只为 x86_64 架构提供编译后的二进制文件，但为其他架构提供 docker 镜像，包括 arm64 和 armv7。如果您想在 Raspberry Pi 上运行 SQLPage 或
更便宜的 ARM 云实例，使用 docker 镜像是最简单的方法。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="27781897" _msthash="337">在 Mac OS 上，使用 homebrew</h3><a id="user-content-on-mac-os-with-homebrew" class="anchor" aria-label="永久链接：在 Mac OS 上，使用 homebrew" href="#on-mac-os-with-homebrew" _mstaria-label="837564" _msthash="338"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="95145531" _msthash="339">Mac OS 用户的另一种选择是使用 <a href="https://formulae.brew.sh/formula/sqlpage" rel="nofollow" _istranslated="1">SQLPage 的 homebrew 包</a>。</p>
<ul dir="auto">
<li><a href="https://brew.sh/" rel="nofollow" _msttexthash="5913453" _msthash="340">安装 homebrew</a></li>
<li><font _mstmutation="1" _msttexthash="64481924" _msthash="341">在终端中，运行以下命令：</font><ul dir="auto">
<li><code>brew install sqlpage</code></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11673467" _msthash="342">运作方式</h2><a id="user-content-how-it-works" class="anchor" aria-label="永久链接：工作原理" href="#how-it-works" _mstaria-label="453388" _msthash="343"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/sqlpage/SQLPage/blob/main/docs/architecture-detailed.png"><img src="/sqlpage/SQLPage/raw/main/docs/architecture-detailed.png" alt="架构图" style="max-width: 100%;" _mstalt="417482" _msthash="344"></a></p>
<p dir="auto"><font _mstmutation="1" _msttexthash="4349628868" _msthash="345">SQLPage 是用 <a href="https://en.wikipedia.org/wiki/Rust_(programming_language)" rel="nofollow" _mstmutation="1" _istranslated="1">Rust</a> 编写的 <a href="https://en.wikipedia.org/wiki/Web_server" rel="nofollow" _mstmutation="1" _istranslated="1">Web 服务器</a>，并作为单个可执行文件分发。
当它收到对以 结尾的 URL 的请求时，它会找到相应的
SQL 文件，在数据库上运行它，
将 Web 请求中的信息作为 SQL 语句参数传递。
当数据库开始返回查询的行时，
SQLPage 将行中的每条信息映射到一个参数
在其预定义组件的模板之一中，并将结果流回
添加到用户的浏览器。</font><code>.sql</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4284137" _msthash="346">例子</h2><a id="user-content-examples-1" class="anchor" aria-label="永久链接：示例" href="#examples-1" _mstaria-label="369876" _msthash="347"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="357954259" _msthash="348"><a href="/sqlpage/SQLPage/blob/main/examples/todo%20application" _istranslated="1">TODO list</a>：一个简单的 todo list 应用程序，演示如何使用 SQLPage 创建基本的 CRUD 应用程序。</li>
<li _msttexthash="626095340" _msthash="349"><a href="/sqlpage/SQLPage/blob/main/examples/plots%20tables%20and%20forms" _istranslated="1">绘图、表格、表单和交互性</a>：一个简短的注释详尽的演示，展示了如何使用绘图、表格、表单和交互性根据 URL 参数筛选数据。</li>
<li _msttexthash="136792669" _msthash="350"><a href="/sqlpage/SQLPage/blob/main/examples/splitwise" _istranslated="1">Tiny splitwise clone</a>：共享费用跟踪应用程序</li>
<li _msttexthash="115082435" _msthash="351"><a href="/sqlpage/SQLPage/blob/main/examples/corporate-conundrum" _istranslated="1">Corporate Conundrum</a>：用 SQL 实现的棋盘游戏</li>
<li _msttexthash="358947420" _msthash="352"><a href="/sqlpage/SQLPage/blob/main/examples/master-detail-forms" _istranslated="1">主从表单</a>：说明如何实现一组简单的表单，以将数据插入到具有一对多关系的数据库表中。</li>
<li _msttexthash="144077401" _msthash="353"><a href="/sqlpage/SQLPage/blob/main/examples/official-site" _istranslated="1">SQLPage 自己的官网和文档</a>：项目官网的 SQL 源码 <a href="https://sql.datapage.app" rel="nofollow" _istranslated="1">https://sql.datapage.app</a></li>
<li _msttexthash="561608125" _msthash="354"><a href="/sqlpage/SQLPage/blob/main/examples/image%20gallery%20with%20user%20uploads" _istranslated="1">图片库</a>：用户可以登录并上传图片的图片库。阐释如何使用会话 Cookie 实现用户身份验证系统，以及处理文件上传。</li>
<li _msttexthash="271576383" _msthash="355"><a href="/sqlpage/SQLPage/blob/main/examples/user-authentication" _istranslated="1">用户管理</a>：包含用户注册、登录、注销和机密页面的身份验证演示。使用 PostgreSQL。</li>
<li _msttexthash="521565824" _msthash="356"><a href="/sqlpage/SQLPage/blob/main/examples/using%20react%20and%20other%20custom%20scripts%20and%20styles" _istranslated="1">制作 JSON API 并在前端集成 React 组件</a>：展示如何在 SQLPage 网站中集成 React 组件，以及如何使用 SQLPage 轻松构建 REST API。</li>
<li _msttexthash="309580622" _msthash="357"><a href="/sqlpage/SQLPage/blob/main/examples/image%20gallery%20with%20user%20uploads" _istranslated="1">处理文件上传</a>：一个图像库，经过身份验证的用户可以通过上传表单发布新图像。</li>
<li _msttexthash="323955723" _msthash="358"><a href="/sqlpage/SQLPage/blob/main/examples/official-site/examples/handle_csv_upload.sql" _istranslated="1">从 CSV 文件批量导入数据</a> ：一种简单的表单，允许用户导入 CSV 文件以填充数据库表。</li>
<li><a href="https://github.com/mnesarco/sqlpage_auth_example" _msttexthash="134886310" _msthash="359">使用 PostgreSQL 存储过程的高级身份验证示例</a></li>
<li><a href="https://github.com/DSMejantel/Ecole_inclusive" _msttexthash="369996744" _msthash="360">SQLite 中的复杂 Web 应用程序，具有用户管理、文件上传、绘图、地图、表格、菜单等功能</a></li>
<li _msttexthash="736564556" _msthash="361"><a href="/sqlpage/SQLPage/blob/main/examples/single%20sign%20on" _istranslated="1">单点登录</a>：如何在 SQLPage 中实施 OAuth 和 OpenID Connect （OIDC） 身份验证的示例。该演示还包括一个 CAS （Central Authentication Service） 客户端。</li>
<li _msttexthash="359384220" _msthash="362"><a href="/sqlpage/SQLPage/blob/main/examples/light-dark-toggle" _istranslated="1">深色主题</a> ：演示如何让用户在浅色主题和深色主题之间切换，并存储用户的首选项。</li>
</ul>
<p dir="auto" _msttexthash="453934663" _msthash="363">您可以使用 <a href="https://replit.com/@pimaj62145/SQLPage" rel="nofollow" _istranslated="1">SQLPage 在 replit 上的在线演示</a>在线尝试所有示例，而无需在计算机上安装任何内容。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6777615" _msthash="364">配置</h2><a id="user-content-configuration" class="anchor" aria-label="永久链接： 配置" href="#configuration" _mstaria-label="559312" _msthash="365"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="299050765" _msthash="366">SQLPage 可以通过放置在 中的配置文件或环境变量（如 或 ）进行配置。</font><code>sqlpage/sqlpage.json</code><code>DATABASE_URL</code><code>LISTEN_ON</code></p>
<p dir="auto" _msttexthash="55686943" _msthash="367">有关更多信息，请阅读 <a href="/sqlpage/SQLPage/blob/main/configuration.md" _istranslated="1"><code _istranslated="1">configuration.md</code></a>。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="218093135" _msthash="368">此外，还可以通过将 <a href="https://handlebarsjs.com/guide/" rel="nofollow" _mstmutation="1" _istranslated="1"><code _istranslated="1">.handlebars</code></a> 文件放在 中来创建自定义组件。<a href="/sqlpage/SQLPage/blob/main/sqlpage/templates/card.handlebars" _mstmutation="1" _istranslated="1">示例</a>。</font><code>sqlpage/templates</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9417499" _msthash="369">HTTPS 协议</h3><a id="user-content-https" class="anchor" aria-label="永久链接：HTTPS" href="#https" _mstaria-label="246480" _msthash="370"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="1928971642" _msthash="371">SQLPage 原生且透明地支持 HTTP/2 和 HTTPS。
只需设置 ， 和 SQLPage
将自动请求受信任的证书，并且
开始使用它加密所有用户的流量。
无需繁琐的手动配置，
并且不会为您的用户提供烦人的“连接不安全”消息！</font><code>SQLPAGE_HTTPS_DOMAIN=example.com</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="10467405" _msthash="372">无服务器</h2><a id="user-content-serverless" class="anchor" aria-label="永久链接：无服务器" href="#serverless" _mstaria-label="447746" _msthash="373"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="598938236" _msthash="374">您可以通过将 SQLpage 无服务器编译为 <a href="https://aws.amazon.com/lambda/" rel="nofollow" _istranslated="1">AWS Lambda 函数</a>来运行 SQLpage <a href="https://en.wikipedia.org/wiki/Serverless_computing" rel="nofollow" _istranslated="1">无服务器</a>。
一种简单的方法是使用提供的 docker 镜像：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre> docker build -t sqlpage-lambda-builder <span class="pl-c1">.</span> -f lambda.Dockerfile --target builder
 docker run sqlpage-lambda-builder cat deploy.zip <span class="pl-k">&gt;</span> sqlpage-aws-lambda.zip</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value=" docker build -t sqlpage-lambda-builder . -f lambda.Dockerfile --target builder
 docker run sqlpage-lambda-builder cat deploy.zip > sqlpage-aws-lambda.zip" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="522861066" _msthash="375">然后，您只需将自己的 SQL 文件添加到 ，
并将其<a href="https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-package.html#gettingstarted-package-zip" rel="nofollow" _mstmutation="1" _istranslated="1">上传到 AWS Lambda</a>，
选择 <em _mstmutation="1" _istranslated="1">Amazon Linux 2 上的自定义运行时</em>作为运行时。</font><code>sqlpage-aws-lambda.zip</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="44712616" _msthash="376">直接在数据库中托管 sql 文件</h3><a id="user-content-hosting-sql-files-directly-inside-the-database" class="anchor" aria-label="永久链接：直接在数据库内托管 sql 文件" href="#hosting-sql-files-directly-inside-the-database" _mstaria-label="2155010" _msthash="377"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1688890957" _msthash="378">在运行无服务器时，您可以将 SQL 文件直接包含在您正在部署的映像中。
但是，如果您希望能够在不创建新映像的情况下动态更新 sql 文件，
您可以将文件直接存储在数据库内部的表中，该表具有以下结构：</p>
<div class="highlight highlight-source-sql notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">CREATE</span> <span class="pl-k">TABLE</span> <span class="pl-en">sqlpage_files</span>(
  <span class="pl-k">path</span> <span class="pl-k">VARCHAR</span>(<span class="pl-c1">255</span>) <span class="pl-k">NOT NULL</span> <span class="pl-k">PRIMARY KEY</span>,
  contents BLOB,
  last_modified <span class="pl-k">TIMESTAMP</span> DEFAULT <span class="pl-c1">CURRENT_TIMESTAMP</span>
);</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="CREATE TABLE sqlpage_files(
  path VARCHAR(255) NOT NULL PRIMARY KEY,
  contents BLOB,
  last_modified TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="601053739" _msthash="379">确保每次更新文件时都进行更新（或在 TRIGGER 中执行此操作）。
SQLPage 仅在文件被修改后才会从数据库中重新解析文件。</font><code>last_modified</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="23044437" _msthash="380">使用的技术和库</h2><a id="user-content-technologies-and-libraries-used" class="anchor" aria-label="永久链接：使用的技术和库" href="#technologies-and-libraries-used" _mstaria-label="1322217" _msthash="381"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li _msttexthash="139605089" _msthash="382"><a href="https://actix.rs/" rel="nofollow" _istranslated="1">actix web</a> 以令人难以置信的速度处理 HTTP 请求，</li>
<li _msttexthash="134025554" _msthash="383"><a href="https://preview.tabler.io" rel="nofollow" _istranslated="1">Tabler</a> 处理具有专业外观的干净组件的样式，</li>
<li _msttexthash="166095449" _msthash="384"><a href="https://tabler-icons.io" rel="nofollow" _istranslated="1">Tabler 图标</a>是您可以直接从 SQL 中选择的一大组图标，</li>
<li _msttexthash="140845263" _msthash="385"><a href="https://handlebarsjs.com/guide/" rel="nofollow" _istranslated="1">handlebars</a> 从每个组件的可读模板中呈现 HTML 页面。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="25404483" _msthash="386">常见问题解答</h2><a id="user-content-frequently-asked-questions" class="anchor" aria-label="永久链接：常见问题" href="#frequently-asked-questions" _mstaria-label="1089842" _msthash="387"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><strong _msttexthash="245903567" _msthash="388">为什么使用 SQL 而不是真正的编程语言？SQL 甚至不是<a href="https://en.wikipedia.org/wiki/Turing_completeness" rel="nofollow" _istranslated="1">图灵完备</a>的！</strong></p>
</blockquote>
<ul dir="auto">
<li _msttexthash="1544679643" _msthash="389">你关注的问题不对。如果您可以以声明方式表达您的应用程序，那么您应该这样做 — 无论是使用 SQL 还是其他语言。与命令式代码相比，声明性代码通常更简洁、可读性更强、更易于推理且更易于调试。</li>
<li _msttexthash="258605945" _msthash="390">SQL 比传统语言更简单，通常非程序员也能阅读，但功能非常强大。</li>
<li _msttexthash="165679956" _msthash="391">如果你的目标是复杂性，请注意 <a href="https://stackoverflow.com/questions/900055/is-sql-or-even-tsql-turing-complete/7580013#7580013" rel="nofollow" _istranslated="1">SQL 实际上是图灵完备</a>的。</li>
<li _msttexthash="797656197" _msthash="392">即使没有递归查询，由用户交互（如 SQLPage）驱动的一系列 SQL 语句仍然是图灵完备的，使您能够构建一个充当图灵机的 SQL 驱动的网站。</li>
</ul>
<blockquote>
<p dir="auto" _msttexthash="133747380" _msthash="393"><strong _istranslated="1">仅仅因为你可以并不意味着你应该......</strong><br _istranslated="1"> — <a href="https://www.reddit.com/r/rust/comments/14qjskz/comment/jr506nx" rel="nofollow" _istranslated="1">有人在 Reddit 上刻薄</a></p>
</blockquote>
<p dir="auto" _msttexthash="690984879" _msthash="394">这不是关于“应该”——而是关于“为什么不”？
如果您愿意，请继续在线条内着色，但我们会在这里享受我们的 SQL 网站的乐趣。</p>
<blockquote>
<p dir="auto"><strong _msttexthash="52447499" _msthash="395">这与 Microsoft Access 相同吗？</strong></p>
</blockquote>
<p dir="auto" _msttexthash="217079876" _msthash="396">目标相似 — 创建简单的以数据为中心的应用程序 — 但工具差异很大：</p>
<ul dir="auto">
<li _msttexthash="130751777" _msthash="397">SQLPage 是 Web 服务器，而不是桌面应用程序。</li>
<li _msttexthash="181224654" _msthash="398">SQLPage 连接到现有的健壮关系数据库;Access 尝试<strong _istranslated="1">成为</strong>数据库。</li>
<li _msttexthash="84872476" _msthash="399">访问是昂贵的和专有的;SQLPage 是<a href="/sqlpage/SQLPage/blob/main/LICENSE.txt" _istranslated="1">开源的</a>。</li>
<li _msttexthash="91407368" _msthash="400">SQLPage 使您免于<a href="https://en.wikipedia.org/wiki/Visual_Basic_for_Applications" rel="nofollow" _istranslated="1">使用 Visual Basic for Applications</a> 的折磨。</li>
</ul>
<blockquote>
<p dir="auto"><strong _msttexthash="56738669" _msthash="401">该名称是否引用了 Microsoft FrontPage？</strong></p>
</blockquote>
<p dir="auto" _msttexthash="393235427" _msthash="402">FrontPage 是 90 年代后期流行的视觉静态网站构建器。直到有人问我，我才听说过它。</p>
<blockquote>
<p dir="auto"><strong _msttexthash="111145294" _msthash="403">我喜欢 CSS。我想设计网站，而不是编写 SQL。</strong></p>
</blockquote>
<p dir="auto"><font _mstmutation="1" _msttexthash="1809358811" _msthash="404">如果你想编写自己的 HTML 和 CSS，
您可以通过在 <a href="https://handlebarsjs.com/guide/" rel="nofollow" _mstmutation="1" _istranslated="1"><code _istranslated="1">.handlebars</code></a> 文件中添加 HTML 和 CSS 并在其中编写 HTML 和 CSS 来<a href="https://sql.datapage.app/custom_components.sql" rel="nofollow" _mstmutation="1" _istranslated="1">创建自定义组件</a>。（<a href="/sqlpage/SQLPage/blob/main/sqlpage/templates/alert.handlebars" _mstmutation="1" _istranslated="1">示例</a>）。
您还可以使用该组件编写原始 HTML，或使用该组件包含自定义脚本和样式。</font><code>sqlpage/templates</code><code>html</code><code>shell</code></p>
<p dir="auto" _msttexthash="907284183" _msthash="405">但 SQLPage 认为，在您拥有工作原型之前，您不应该担心按钮边框半径。
我们提供开箱即用的美观组件，因此您可以专注于数据模型并快速迭代。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5638321" _msthash="406">下载</h2><a id="user-content-download" class="anchor" aria-label="永久链接： 下载" href="#download" _mstaria-label="367133" _msthash="407"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="64178530" _msthash="408">SQLPage 可从多个来源下载：</p>
<p dir="auto"><a href="https://github.com/lovasoa/SQLpage/releases/latest"><img src="https://camo.githubusercontent.com/60f946df3f232aa084916d5e2051485afe4a0cb209ed7b14dabe617a39dc778d/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f646f776e6c6f6164732f6c6f7661736f612f73716c706167652f746f74616c3f6c6162656c3d646972656374253230646f776e6c6f6164" alt="GitHub 下载（所有资源、所有版本）" data-canonical-src="https://img.shields.io/github/downloads/lovasoa/sqlpage/total?label=direct%20download" style="max-width: 100%;" _mstalt="1253122" _msthash="409"></a>
<a href="https://hub.docker.com/r/lovasoa/sqlpage" rel="nofollow"><img src="https://camo.githubusercontent.com/56dbabeafa8be50c0f45fda652fd2ae6da8198784ba9228f1131b644963c4338/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f6c6f7661736f612f73716c706167653f6c6162656c3d646f636b65722533412532306c6f7661736f6125324673716c70616765" alt="Docker 拉取" data-canonical-src="https://img.shields.io/docker/pulls/lovasoa/sqlpage?label=docker%3A%20lovasoa%2Fsqlpage" style="max-width: 100%;" _mstalt="179205" _msthash="410"></a>
<a href="https://formulae.brew.sh/formula/sqlpage#default" rel="nofollow"><img src="https://camo.githubusercontent.com/a152131dea898344cf697bf8bf9fc287a6ade2553f1e43e8437b9ecf94d3cf8d/68747470733a2f2f696d672e736869656c64732e696f2f686f6d65627265772f696e7374616c6c732f64712f73716c706167653f6c6162656c3d686f6d6562726577253230646f776e6c6f616473266c6162656c436f6c6f723d25323332653261323426636f6c6f723d253233663964303934" alt="Homebrew 下载" data-canonical-src="https://img.shields.io/homebrew/installs/dq/sqlpage?label=homebrew%20downloads&amp;labelColor=%232e2a24&amp;color=%23f9d094" style="max-width: 100%;" _mstalt="357045" _msthash="411"></a>
<a href="https://scoop.sh/#/apps?q=sqlpage&amp;id=305b3437817cd197058954a2f76ac1cf0e444116" rel="nofollow"><img src="https://camo.githubusercontent.com/6374ef84c5efcf9b1b292e62eb04a2a0f9fa17feb96e5c98e4415d2d4f10f059/68747470733a2f2f696d672e736869656c64732e696f2f73636f6f702f762f73716c706167653f6c6162656c436f6c6f723d25323336393635373326636f6c6f723d253233643764346462" alt="Scoop 版本" data-canonical-src="https://img.shields.io/scoop/v/sqlpage?labelColor=%23696573&amp;color=%23d7d4db" style="max-width: 100%;" _mstalt="207051" _msthash="412"></a>
<a href="https://crates.io/crates/sqlpage" rel="nofollow"><img src="https://camo.githubusercontent.com/353449e1321a1459077f04189f71f1769d9bbfd288562a618363c465b53a521c/68747470733a2f2f696d672e736869656c64732e696f2f6372617465732f642f73716c706167653f6c6162656c3d6372617465732e696f253230646f776e6c6f6164266c6162656c436f6c6f723d25323332363433323326636f6c6f723d253233663966376563" alt="Crates.io 总下载量" data-canonical-src="https://img.shields.io/crates/d/sqlpage?label=crates.io%20download&amp;labelColor=%23264323&amp;color=%23f9f7ec" style="max-width: 100%;" _mstalt="553111" _msthash="413"></a>
<a href="https://search.nixos.org/packages?channel=unstable&amp;show=sqlpage&amp;from=0&amp;size=50&amp;sort=relevance&amp;type=packages&amp;query=sqlpage" rel="nofollow"><img src="https://camo.githubusercontent.com/299d493b169c7c8b03bd737225e17c596ecb8a8245a85eb5721014c0849cac0e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e69782d706b672d726762283132362c2532303138352c25323032323729" alt="" data-canonical-src="https://img.shields.io/badge/Nix-pkg-rgb(126,%20185,%20227)" style="max-width: 100%;"></a></p>
</article></div>
