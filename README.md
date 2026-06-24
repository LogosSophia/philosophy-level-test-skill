# 哲学水平测试.skill
# Philosophy Level Test Skill

你真的在思考哲学，还是只是在堆砌高级词汇？

Are you really thinking philosophically, or just stacking impressive words?

输入一段哲学观点、人生感悟、理论草稿、诗性表达或宏大判断，本 skill 会对它进行哲学压力测试：检查它是否存在对象未成立、位置非法、位置滑坡、概念漂移、本质滑坡、尺度漂移、非法综合、伪整体、隐喻冒充本体、情绪代替论证和伪深刻等问题。

Input a philosophical idea, life reflection, theoretical draft, poetic expression, or grand claim. This skill runs a philosophical stress test on it, checking for unqualified objects, invalid speaking positions, position drift, concept drift, essence slide, scale drift, illegal synthesis, pseudo-wholes, metaphor mistaken for ontology, emotion replacing argument, and pseudo-depth.

它测试的不是学历，不是知识量，也不是你读过多少哲学家，而是一段思考能不能承担自己的概念成本。

It does not test your degree, your knowledge volume, or how many philosophers you have read. It tests whether a piece of thought can bear the conceptual cost of what it says.

> 输入一段你的哲学观点，看看它是思想，还是伪深刻。
>
> Input your philosophical idea and see whether it is real thought or pseudo-depth.

---

## 快速入口 / Quick Links

- [核心 Skill / Core Skill](./philosophy_level_test.skill.md)
- [说话位置规则 / Speaking Position Rules](./rules_position.md)
- [快速开始 / Quickstart](./QUICKSTART.md)
- [Prompt 模板 / Prompt Templates](./prompt_templates.md)
- [评分说明 / Scoring Guide](./scoring.md)
- [术语表 / Glossary](./glossary.md)
- [示例 / Examples](./examples.md)
- [路线图 / Roadmap](./ROADMAP.md)
- [贡献指南 / Contributing](./CONTRIBUTING.md)
- [授权说明 / License](./LICENSE.md)

---

## 它会输出什么？ / What does it output?

- 哲学水平评分 / Philosophy score
- 思想段位 / Thought level
- 伪深刻指数 / Pseudo-depth index
- 核心命题 / Core thesis
- 最强之处 / Strongest point
- 最大漏洞 / Major flaw
- 致命追问 / Fatal questions
- 修改建议 / Revision advice

---

## 快速使用 / Quick Use

把 [`philosophy_level_test.skill.md`](./philosophy_level_test.skill.md) 的内容复制到你使用的 AI 工具、智能体 system prompt、自定义指令或知识库中，然后发送一段哲学思考即可。

Copy the content of [`philosophy_level_test.skill.md`](./philosophy_level_test.skill.md) into your AI tool, agent system prompt, custom instruction, or knowledge base. Then send a piece of philosophical writing for testing.

示例输入 / Example input:

```text
我认为自由就是摆脱一切限制。真正自由的人不应该被任何规则束缚。
```

可能输出 / Possible output:

```text
哲学水平评分：48/100
段位：有问题意识的思考者
伪深刻指数：55/100
最大漏洞：概念偷换、尺度漂移、结论冒充前提
致命追问：如果自由是完全没有限制，那么它如何区别于虚无？
```

---

## 核心审查项 / Core Checks

1. **对象未成立 / Unqualified Object**  
   把一个词当成已经存在的对象来讨论，却没有说明它是什么、边界在哪里、如何被切出来。

2. **位置非法 / Invalid Position**  
   站在边界之内，却声称自己把握到了边界本身、边界整体或边界之外。注意：位置不是唯物主义、唯心主义等理论立场。

3. **位置滑坡 / Position Drift**  
   文本不断更换说话层级，却没有说明自己何时从一个位置转到另一个位置。

4. **概念漂移 / Concept Drift**  
   同一个词在文本中前后换了意思，但作者没有承认自己换了意思。

5. **本质滑坡 / Essence Slide**  
   用“本质”“归根到底”“说到底”等词，把本来需要论证的层级转换、因果转换、对象转换直接跳过。

6. **尺度漂移 / Scale Drift**  
   从小范围判断突然跳到大范围结论，中间没有说明放大机制。

7. **非法综合 / Illegal Synthesis**  
   把已经被切分、定义、抽象、记录、比喻或跨尺度转译后的碎片，重新拼成一个据称等同于原对象、原发生或整体的东西。

8. **伪整体 / Pseudo-Whole**  
   把无法合法看见或切出的整体，说成一个已经被把握的完整对象。

9. **隐喻冒充本体 / Metaphor Mistaken for Ontology**  
   本来只是比喻、诗性表达或情绪图像，却被当成真实结构来论证。

10. **伪深刻 / Pseudo-Depth**  
    用宏大词汇、神秘气氛或矛盾包装制造深度感，但没有承担概念成本。

---

## 项目结构 / Repository Structure

```text
philosophy-level-test-skill/
├── README.md
├── philosophy_level_test.skill.md
├── rules_position.md
├── QUICKSTART.md
├── prompt_templates.md
├── scoring.md
├── glossary.md
├── examples.md
├── ROADMAP.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CITATION.cff
├── LICENSE.md
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bad-output.md
    │   └── rule-suggestion.md
    └── pull_request_template.md
```

---

## 适用场景 / Use Cases

- 哲学观点 / Philosophical ideas
- 人生感悟 / Life reflections
- 理论草稿 / Theoretical drafts
- 社会评论 / Social commentary
- 玄学表达 / Metaphysical or mystical claims
- 诗歌解读 / Poetic interpretations
- 自创体系 / Self-created theoretical systems
- 宏大叙事 / Grand narratives
- AI 生成哲学段落 / AI-generated philosophical text

---

## 版本 / Version

当前版本：v0.2.0

Current version: v0.2.0

详见 [`CHANGELOG.md`](./CHANGELOG.md)。

See [`CHANGELOG.md`](./CHANGELOG.md).

---

## 授权 / License

本项目暂定采用 CC BY-NC-SA 4.0 授权。详见 [`LICENSE.md`](./LICENSE.md)。

This project is provisionally released under CC BY-NC-SA 4.0. See [`LICENSE.md`](./LICENSE.md).

---

## 重要说明 / Important Note

本 skill 批判的是文本，不是人格。它可以犀利，但不应羞辱用户。评分越低，不代表用户越差，只代表这段文本还没有承担它使用的概念成本。

This skill critiques the text, not the person. It may be sharp, but it should not humiliate the user. A lower score does not mean the user is inferior; it means the submitted text has not yet borne the conceptual cost of its own claims.
