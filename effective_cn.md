# 高效开发手册
- By Edmond Lau
- translate by guolei
- Highly Recommended :+1:
- http://www.theeffectiveengineer.com/

### 什么是高效开发者
- 开发程序并产生好的结果[ps: 帮老板省钱，赚钱]

## 下面是我的想法

### 专注高效的活动
- Leverage = 产出/时间成本
- 高效产出作为衡量标准
- 做20%的工作完成80的需求   
- 专注更有价值的部分，并不是简单的不知黏贴

### 优化学习方法
- 换工作如果有必要的话[现有工作不能提升自己]
- 优化学习方法[理解并讲出来，动手实践]
- 以下是我的几点想法
  - 跟同事交流,寻求更好的解决方法
  - 多多实践，量变到质变
  - 完成更多成功的案例

-  改进学习效率
  - 工欲善其事必先利其器
  - 完成更有挑战的工作
  - 如果持续学习收益降低，想办法改善它
  - 投入更多的时间学习实践

- 寻找更好的办公环境
  - 快速成长: 解决问题,做更有挑战的工作
  - Make sure you are working on high priority projects.
  - 确保你在做对你有提升的项目[不是闭眼转圈拉磨]
  - 开放: 求知多问,不耻下问[三人行必有我师]
  - 快节奏的开发.
  - 和比你聪明的人一起工作
  - 自觉自律: 选在喜欢的项目自主完成[越小的公司越好]

- 关于工作
  - 养成每天学习新技能
  - 阅读优秀开发着的代码
  - 跳过自己无法理解的代码[允许无知]
  - 持续学习.学习最有需求的技能知识.
  - 人穷多读书,读的越多才能一览众山小.
  - 保持好的人际关系

### 一般优先级
- 坏的工作方向,影响是深远的[找对方向,不能南辕北辙]
- 付出的和回报要成正比
- Regular prioritization is high leverage activity.
- 做TODO列表
  - 分解工作任务到列表
  - 不要试图记住所有东西，用的时候查文档
- 经常问自己： 这事情是我最优先级处理的么？
- 专注更有价值的东西
- 学会说不
- 关注重要的任务而不是紧急的任务
- 进入到废寝忘食的状态，并保持热情
- 如果可能，尽量避免耗时的任务[可能是任务分解不够细]
- 控制工作节奏,尽量不让外界打扰
  - 思考被中断，来回做不同的任务很浪费时间
- Prioritizing is difficult.排序优先级很难
- 专注把正确的事情做完美


### 投入持续集成的怀抱
-  持续集成很有帮助
  - 自动部署可以帮助开发人员节省部署时间
- 快速行动，快速学习
  - 分解要学习的知识，并快速学习
  - 快速行动能让你做并学习更多的事情,
-  投入时间使用能够帮你省时间的工具[善用佳软]   
  - 如果一件事情做过两次，第三次写脚本,自动化你的工作
  - 善用工具,三头六臂，大显神通.
  - 经常使用效率高的工具
  - 高效工具能是新的流畅更加高效
  - Productivity skyrockets with tools.
  - 高效工具
  - Time saving property of tools also scale with team adoption.
-  缩短代码调试和验证  
  - 优化调试流程能够减少让人头疼的bug
  - 代码调试很让人头疼.是时候投入资源,优化调试时间

- High test coverage to reduce build and site breakages.
- 高质量的代码覆盖能够减少构建
- 单元测试能够激励人们测试构建程序
- 快速增量编译能减少开发等待时间。

- 专业化开发环境
  - 同一种工具 同一种高级开发语言,脚本语言，甚至是硬件环境[统一的软件和]
  One editor. One high level language. Shell. Keyboard > Mouse. Automate manual workflows. Use interactive shell. Make running specific tests easy.
** Faster you can iterate, faster you can learn.**

### 量化你要改进的东西
- 用量化驱动
  - 如果不能量化，就没办法改进
  - 量化的好处
    - 帮助你专注重要的事情
    - 驱动你向前走
    - 帮助你评估未来进程
    - **Performance Ratcheting**: Any change should strictly improve the metric.  
    - 任何变化应该严格量化评估
    - 错误的量化会导致错误的结果
    - 比如:
      - 高效工作的时间
      - 行为统计[idea helps short key caculations]

  - 量化影响你的决策和行动
  - 对比团队量化统计前后，量化影响并改进你的团队
  - 行为量化 -- 谁对团队的效率提升最大
  - 量化相应的结果 -- 快速反馈变化的结果
  - 选择量化指标非常重要
  - 决策使用正确的量化指标
- 量化并可视化任何事情，让你知道到底发生了什么。
  - 量化任何事情,量化所有事情
  - Graphite ,statsd. 一行简单的命令让你定义一个新的指标.
  - 量化你想要达成的目标
- Internalize useful numbers  
  - Knowledge of useful numbers provide a valuable shortcut for knowing where to invest efforts to maximize gains.
  - Need upfront work. Need not be accurate, ballpark idea suffices.
  - Knowing useful numbers enables you to do back of the envelope calculations to quickly estimate the perrmance properties of a design without actually building it.
  - Internalizing useful number help you spot anamalies.
Be skeptical about data integrity.
 - log data liberally.
 - Build tools to iterate on data accuracy sooner.
 - Examine data sooner.
 - When numbers look off, dig in to it sooner.

:heavy_check_mark: Measure your progress. Carefully choose your top-level metric. Instrument your system. Know your numbers. Prioritize data integrity.

### Validate your ideas early and often.
- Not validating early leads to wasted efforts.
- Dont delay get feedback.
- Find low effort ways to validate work.
- Power of small batches. Helps you avoid making a big mistake by stopping the flow.
- Approach problem iteratively.
- No large implementations.
- Working solo? Be wary. Be extra vocal and get feedback.

### Improve project estimation skills.
- Beware of mythical man month. Communication overhead is significant.
- Reduce risk early
- Rewrite projects - almost always fail.
- Additional hours hurt prooductivity. Causes burnout.
- Do the riskiest task first.
- Allow buffer room for the unknown.

### Balance Quality with Pragmatism
- High codequality. Code readability.
- Establish sustainable code review process.
- Code reviews help:
  - Catch bugs and design problems early.
  - Sharing working knowledge of the codebase.
  - Increases long term agility. Easier to unerstand, quicker to modify.

#### Manage complexity through Abstraction  
- Example: MapReduce
- Right abstractions make huge difference.
- “Pick the right ones, and programming will flow naturally from design; modules will have small and simple interfaces; and new functionality will more likely fit in without extensive reorganization,”
- “Pick the wrong ones, and programming will be a series of nasty surprises: interfaces will become baroque and clumsy as they are forced to accommodate unanticipated interactions, and even the simplest of changes will be hard to make.”
- The right abstraction can increase engineering productivity by an order of magnitude.
- Simple abstractions avoid interweaving multiple concepts, so that you can reason about them independently rather than being forced to consider them together.
- Designing good abstractions take work.
- An abstraction's usage and popularity provides a reasonable proxy for it's quality.

#### Automate Testing
- Unit test cases and some integration testing provide a scalable way of managing growing codebase.
- A suite of extensive and automated tests can reduce overall error rates by validating the quality and by safeguardingagainst regressions.
- Tests also allow engineers to make changes, especially large refactorings, with significantly higher confidence.
- Despite its benefits, it can be difficult to foster a culture of automated testing.
- Focus on high leverage tests.
- Writing more tests, creating a virtuous feedback cycle and saving more development time.

#### Repay Techincal Debt
- Technical debt refers to all the deferred work that’s necessary to improve the health and quality of the codebase and that would slow us down if left unaddressed.
- Accumulating technical debt is fine as far as it is repaid within time.
- Refactor often.


### Reduce Operational Complexity
- Keep no. of technologies low. Don’t sway towards shiny new technologies.
- Every additional technology you add is is guaranteed to go worong eventually. Will need your time.
- Do the simple thing first
- Embrace operational simplicity.
- The first solution that comes to mind is generally complex. Don't stop. Keep peeling off the layers of onion.
- Simplify the architecture to reduce their operational burden.
- “What’s the simplest solution that can get the job done while also reducing our future operational burden?”
- Discipline to focus on simplicity is high leverage.

### Fail Fast
- Fail immediately and visibly.
- doesn’t necessarily mean crashing your programs for users
- fail-fast to surface issues immediately
- Failing fast is high leverage as it saves devugging time.

### Relentlessly Automate
- Automating mechanics is good.
- Automating decision making - no.
- Hone Your Ability to Respond and Recover Quickly
    - Leverage ( Recovering quickly ) > Leverage ( Preventing Failures )
- “script for success,” practice failure scenarios, and work on our ability to recover quickly.
- Make batch process idempotent
- Make processes retrable i.e. not leaving any global state.

### Invest in your team's Growth
- Invest in onboarding.
- The higher you climb up the engineering ladder, the more your effectiveness will be measured not by your individual contributions but by your impact on the people around you.
- **"You’re a staff engineer if you’re making a whole team better than it would be otherwise. You’re a principal engineer if you’re making the whole company better than it would be otherwise. And you’re distinguished if you’re improving the industry.”**
￼- Focus primarily on making everyone around you succeed.
- Your career depends on your team's success.
- Make hiring everyone's responsibility.
- Shared ownership of code.
  - Keep bus factor more than one.
  - Shared ownershop removes isolated silos of information.
- Build collective wisdom through post mortems.
- Invest in automated testing.
  - Automated testcases lead to higher confidence when refactoring.
  - Write test cases when the code is fresh in mind.
  - Don’t be dogmatic about 100% code coverage.
  - Value of tests increases over time and cost to write goes down.
- Hire the best.
- Surround yourself with great advisors

:sunny: **“Leverage is the lens through which effective engineers view their activities. ”** :sunny:

### 10 Books to read:
- Peopleware Productive projects and Teams. Amazon. My Summary.
- Team Geek: A Software Developer’s Guide to Working Well with Others. (Debugging Teams) Amazon. My Summary.
- High Output Management
- Getting Things Done: The Art of Stress-Free Productivity
- The 4-Hour Workweek: Escape 9-5, Live Anywhere, and Join the New Rich
- The 7 Habits of Highly Effective People: Powerful Lessons in Personal Change
- Conscious Business: How to Build Value Through Values
- Your Brain at Work
- Flow: The Psychology of Optimal Experience
- Succeed: How We Can Reach Our Goals

### Blogs:
“Recommended Blogs To Follow

http://www.theeffectiveengineer.com/. The Effective Engineer is my personal blog, where I write about engineering habits, productivity tips, leadership, and culture.
http://www.kalzumeus.com/. Patrick McKenzie runs his own software business and has written many excellent long-form articles on career advice, consulting, SEO, and software sales.
http://katemats.com/. Kate Matsudaira, who has worked at large companies like Microsoft and Amazon as well as at startups, shares advice about tech, leadership, and life on her blog.”
“http://randsinrepose.com/. Michael Lopp has worked for many years in leadership positions at Netscape, Apple, Palantir, and Pinterest, and writes about tech life and engineering management.
http://softwareleadweekly.com/. Oren Ellenbogen curates a high-quality weekly newsletter on engineering leadership and culture.
http://calnewport.com/. Cal Newport, an assistant professor of computer science at Georgetown, focuses on evidence-based advice for building a successful and fulfilling life.
http://www.joelonsoftware.com/. Joel Spolsky, the co-founder of Stack Exchange, provides all sorts of programming pearls of wisdom on his blog.
http://martinfowler.com/. Martin Fowler, author of the book Refactoring, writes about how to maximize the productivity of software teams and provides detailed write-ups of common programming patterns.
http://pgbovine.net/. Philip Guo, a computer science professor, has written extensively and openly about his graduate school and work experiences.”
