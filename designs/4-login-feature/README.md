- Repo: (the repo it will be implemented in, e.g. Superset/espree)
- Start Date: 2020-08-27
- RFC PR: (leave this empty, to be filled in later)
- Authors: Lanseria

# 登录模块

## Summary 摘要

此 RFCS 讨论登录模块构想

## Motivation 动机

登录模块构想完成以下几点

- 提供登录注册
- 提供用户名
- 登录使用 JWT 方案设计
- 提供刷新 token 功能保持一直在线登录

- 将来限制登录功能
- 将来提供第三方登录服务
- 将来手机号,邮箱登录功能
- 将来提供滑动验证功能
- 将来提供验证码功能

## Detailed Design 详细设计

### 接口设计

[登录接口设计详情](./Interface.md)

## Documentation 文献资料

<!--
    How will this RFC be documented? Does it need a formal announcement
    on the Superset  blog to explain the motivation?
-->

<!--
    如何记录此 RFC ？
    需要正式公告吗在 Superset 博客上解释动机？
-->

## Drawbacks 缺点

<!--
    Why should we *not* do this? Consider why adding this into Superset
    might not benefit the project or the community. Attempt to think
    about any opposing viewpoints that reviewers might bring up.

    Any change has potential downsides, including increased maintenance
    burden, incompatibility with other tools, breaking existing user
    experience, etc. Try to identify as many potential problems with
    implementing this RFC as possible.
-->
<!--

    为什么我们不应该这样做？
    考虑为什么将其添加到 Superset 中可能不会使项目或社区受益。
    尝试思考关于审稿人可能提出的任何相反观点。

    任何变化都有潜在的不利影响，
    包括增加维护负担，
    与其他工具的不兼容，
    破坏了现有用户经验等。
    尝试找出尽可能多的潜在问题尽可能实施此 RFC。
-->

## Backwards Compatibility Analysis 向后兼容性分析

<!--
    How does this change affect existing Superset  users? Will any behavior
    change for them? If so, how are you going to minimize the disruption
    to existing users?
-->

<!--
    此更改如何影响现有的 Superset 用户？
    会不会有任何行为为他们改变？
    如果是这样，您将如何最大程度地减少干扰给现有用户？
-->

## Alternatives 备择方案

<!--
    What other designs did you consider? Why did you decide against those?

    This section should also include prior art, such as whether similar
    projects have already implemented a similar feature.
-->

<!--
    您还考虑其他哪些设计？
    您为什么反对这些？

    本部分还应包括现有技术，
    例如是否类似项目已经实现了类似的功能。
-->

## Open Questions 问题公开

<!--
    This section is optional, but is suggested for a first draft.

    What parts of this proposal are you unclear about? What do you
    need to know before you can finalize this RFC?

    List the questions that you'd like reviewers to focus on. When
    you've received the answers and updated the design to reflect them,
    you can remove this section.
-->
<!--
    本部分是可选的，但建议初稿使用。

    您不清楚该提案的哪些部分？
    你是什​​么在最终确定此 RFC 之前需要知道吗？
    列出您希望审稿人关注的问题。
    什么时候您已经收到答案并更新了设计以反映它们，您可以删除此部分。
-->

## Help Needed 需要帮助

<!--
    This section is optional.

    Are you able to implement this RFC on your own? If not, what kind
    of help would you need from the team?
-->
<!--
    本部分是可选的。

    您能够自己实现此 RFC 吗？
    如果没有，那是什么样的您需要团队的帮助吗？
-->

## Frequently Asked Questions 常见问题

<!--
    This section is optional but suggested.

    Try to anticipate points of clarification that might be needed by
    the people reviewing this RFC. Include those questions and answers
    in this section.
-->
<!--
    本部分是可选的，但建议使用。

    尝试预期可能需要澄清的点审核此 RFC 的人员。
    包括那些问题和答案在这个部分。
-->

## Related Discussions 相关讨论

<!--
    This section is optional but suggested.

    If there is an issue, pull request, or other URL that provides useful
    context for this proposal, please include those links here.
-->
<!--
    本部分是可选的，但建议使用。

    如果有问题，请提供拉取请求或其他有用的网址此提案的上下文，请在此处添加这些链接。
-->
