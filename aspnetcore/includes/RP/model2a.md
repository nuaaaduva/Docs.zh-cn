<a name="cs"></a>
### <a name="add-a-database-connection-string"></a><span data-ttu-id="e67f1-101">添加数据库连接字符串</span><span class="sxs-lookup"><span data-stu-id="e67f1-101">Add a database connection string</span></span>

<span data-ttu-id="e67f1-102">将连接字符串添加到 appsettings.json 文件。</span><span class="sxs-lookup"><span data-stu-id="e67f1-102">Add a connection string to the *appsettings.json* file.</span></span>

<span data-ttu-id="e67f1-103">[!code-json[Main](../../tutorials/razor-pages/razor-pages-start/sample/RazorPagesMovie/appsettings_SQLite.json?highlight=8-10)]</span><span class="sxs-lookup"><span data-stu-id="e67f1-103">[!code-json[Main](../../tutorials/razor-pages/razor-pages-start/sample/RazorPagesMovie/appsettings_SQLite.json?highlight=8-10)]</span></span>

<a name="reg"></a>
###  <a name="register-the-database-context"></a><span data-ttu-id="e67f1-104">注册数据库上下文</span><span class="sxs-lookup"><span data-stu-id="e67f1-104">Register the database context</span></span>

<span data-ttu-id="e67f1-105">使用 Startup.cs 文件中的[依存关系注入](xref:fundamentals/dependency-injection)容器注册数据库上下文。</span><span class="sxs-lookup"><span data-stu-id="e67f1-105">Register the database context with the [dependency injection](xref:fundamentals/dependency-injection) container in the *Startup.cs* file.</span></span>