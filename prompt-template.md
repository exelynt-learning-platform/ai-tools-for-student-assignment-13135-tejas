# Reusable Email Prompt Template

**Tool used:** Claude (Claude Sonnet 5.5, via Claude Code). Answers are pasted unedited.

## Template

```
You are a polite, professional writing assistant helping a college student.
I am [my name], a [year and branch] student. I need to email [person] about [reason].
Key facts: [key facts, e.g. course, dates, what I did].
Write an email that [what I want the person to do]. Tone: [tone].
Format: a subject line, then [number] short paragraphs, under [word limit] words, signed [my name].
```

## Test 1: Asking a professor for a recommendation letter

**Filled-in prompt**

> You are a polite, professional writing assistant helping a college student.
> I am Tejas Bhoite, a final-year Computer Science student. I need to email Prof. Kulkarni about a recommendation letter for my master's application.
> Key facts: I studied Database Systems under him last year and scored an A; the deadline is 30 November.
> Write an email that asks if he can write the letter by 20 November. Tone: respectful.
> Format: a subject line, then 3 short paragraphs, under 120 words, signed Tejas Bhoite.

**Answer**

**Subject: Request for Recommendation Letter: Master's Application**

Dear Prof. Kulkarni,

I hope you are well. I am a final-year Computer Science student, and I am applying for a master's programme. Having studied Database Systems under you last year, where I received an A, I would be honoured if you would write a recommendation letter for me.

My application deadline is 30 November. Would it be possible for you to submit the letter by 20 November? I am happy to share my resume and any details that would help.

Thank you very much for considering my request.

Sincerely,
Tejas Bhoite

## Test 2: Telling a lab instructor about an absence

**Filled-in prompt**

> You are a polite, professional writing assistant helping a college student.
> I am Tejas Bhoite, a final-year Computer Science student. I need to email Ms. Joshi, my lab instructor, about missing Friday's Operating Systems lab for my cousin's wedding.
> Key facts: the lab is on Friday at 2 pm; I can attend the make-up session on Saturday.
> Write an email that asks her to mark my absence as excused and allow a make-up session. Tone: friendly but formal.
> Format: a subject line, then 2 short paragraphs, under 100 words, signed Tejas Bhoite.

**Answer**

**Subject: Request to Miss Friday's Operating Systems Lab**

Dear Ms. Joshi,

I will not be able to attend Friday's 2 pm Operating Systems lab because of my cousin's wedding. I would be grateful if you could mark my absence as excused.

I am available for a make-up session on Saturday, if that suits you. Thank you for your understanding.

Best regards,
Tejas Bhoite

## My Notes

- The same template worked for two very different situations. Only the blanks changed, and each email had the right person, reason and format.
- In both tests the output was only as accurate as the facts I put in the blanks, so I checked names, dates and requests before using them.
- The blanks that mattered most were [key facts] and [tone]. Leaving them out would make the email vague again, as in [vague-vs-clear.md](vague-vs-clear.md).
