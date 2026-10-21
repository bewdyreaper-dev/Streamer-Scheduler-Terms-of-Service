[index.html](https://github.com/user-attachments/files/33744273/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#090608">
  <meta name="description" content="Streamer Scheduler Terms of Service. Review the rules for community participation, streamer promotions, and scheduled showcases.">
  <title>Terms of Service | Streamer Scheduler</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      color-scheme: dark;
      --bg: #090608;
      --panel: #130e12;
      --panel-2: #1c1118;
      --red: #a71935;
      --red-bright: #ed3653;
      --text: #f3eaf0;
      --muted: #b9aab4;
      --border: #40202c;
      --glow: rgba(237, 54, 83, .22);
    }
    * { box-sizing: border-box; scroll-behavior: smooth; }
    body {
      margin: 0; color: var(--text); background:
        radial-gradient(ellipse at 50% -15%, rgba(126, 15, 43, .35), transparent 52%),
        radial-gradient(circle at 5% 35%, rgba(90, 14, 36, .10), transparent 28%), var(--bg);
      font-family: Inter, sans-serif; line-height: 1.75;
    }
    a { color: #ff8195; text-decoration: none; }
    a:hover { color: #fff; }
    .topbar {
      position: sticky; top: 0; z-index: 10; display: flex; align-items: center;
      justify-content: space-between; gap: 18px; padding: 15px clamp(18px, 6vw, 76px);
      background: rgba(9, 6, 8, .93); border-bottom: 1px solid var(--border);
      backdrop-filter: blur(12px);
    }
    .brand { color: #fff; font: 600 18px Cinzel, serif; letter-spacing: 1.5px; }
    .brand span { color: var(--red-bright); }
    .top-link { font-size: 12px; letter-spacing: 1px; text-transform: uppercase; color: var(--muted); }
    .hero { text-align: center; padding: 82px 20px 68px; border-bottom: 1px solid var(--border); }
    .sigil { font-size: 47px; color: var(--red-bright); text-shadow: 0 0 24px var(--glow); line-height: 1.2; }
    .eyebrow { color: #df6278; text-transform: uppercase; letter-spacing: 4px; font-size: 11px; font-weight: 700; margin-top: 18px; }
    h1, h2, h3 { font-family: Cinzel, Georgia, serif; line-height: 1.4; }
    h1 { font-size: clamp(34px, 6vw, 60px); letter-spacing: 1.5px; margin: 10px 0; }
    .hero p { color: var(--muted); max-width: 680px; margin: 12px auto; }
    .button {
      display: inline-block; margin-top: 23px; padding: 12px 23px; border: 1px solid var(--red);
      border-radius: 4px; color: white; background: linear-gradient(135deg, #78152b, #260b14);
      box-shadow: 0 0 24px rgba(167, 25, 53, .16); transition: transform .2s, box-shadow .2s;
      font-size: 12px; font-weight: 700; letter-spacing: 1.2px;
    }
    .button:hover { color: white; transform: translateY(-2px); box-shadow: 0 0 26px var(--glow); }
    .layout { display: grid; grid-template-columns: 230px minmax(0, 760px); gap: 34px; justify-content: center; max-width: 1190px; margin: auto; padding: 48px 22px 82px; }
    .sidebar { align-self: start; position: sticky; top: 88px; padding: 20px 16px; background: rgba(19, 14, 18, .92); border: 1px solid var(--border); border-radius: 7px; }
    .sidebar h3 { color: #e8bdc8; font-size: 13px; margin: 0 0 12px; letter-spacing: 1px; }
    .sidebar nav { display: grid; gap: 2px; }
    .sidebar a { display: block; padding: 6px 9px; border-left: 2px solid transparent; color: var(--muted); font-size: 12px; }
    .sidebar a:hover { color: white; border-left-color: var(--red-bright); background: rgba(167, 25, 53, .10); }
    .content { min-width: 0; }
    .notice { padding: 17px 19px; margin-bottom: 26px; background: rgba(167, 25, 53, .10); border: 1px solid var(--border); border-left: 3px solid var(--red-bright); border-radius: 4px; color: #d7c8d0; font-size: 13px; }
    .notice strong { color: #fff; }
    .term { padding: 25px 0; border-bottom: 1px solid var(--border); scroll-margin-top: 100px; }
    .term h2 { margin: 0 0 12px; color: #f3dce3; font-size: 20px; }
    .num { color: var(--red-bright); margin-right: 8px; }
    .term p, .term li { color: #c5b7c1; font-size: 14px; }
    .term ul { padding-left: 22px; }
    .term li { padding: 3px 0; }
    .contact { margin-top: 30px; padding: 25px; text-align: center; background: linear-gradient(145deg, #21121a, #100b0f); border: 1px solid var(--border); border-radius: 7px; scroll-margin-top: 100px; }
    .contact h2 { font-size: 21px; margin-top: 0; }
    .contact p { color: var(--muted); font-size: 14px; }
    footer { text-align: center; padding: 27px 18px; border-top: 1px solid var(--border); color: #8f7e89; font-size: 12px; }
    footer p { margin: 5px 0; }
    .back { display: inline-block; margin-top: 8px; }
    @media (max-width: 760px) {
      .topbar { padding: 13px 16px; }
      .brand { font-size: 14px; }
      .top-link { font-size: 10px; }
      .hero { padding: 60px 18px 45px; }
      .layout { grid-template-columns: 1fr; gap: 22px; padding: 25px 17px 55px; }
      .sidebar { position: static; }
      .sidebar nav { grid-template-columns: repeat(2, minmax(0, 1fr)); }
    }
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after { scroll-behavior: auto !important; transition: none !important; }
    }
  </style>
</head>
<body id="top">
  <header class="topbar">
    <a class="brand" href="#top">STREAMER <span>SCHEDULER</span></a>
    <a class="top-link" href="#contact">Contact the Keepers</a>
  </header>

  <section class="hero">
    <div class="sigil" aria-hidden="true">☠</div>
    <div class="eyebrow">The rules of the realm</div>
    <h1>Terms of Service</h1>
    <p>Before you enter the schedule, promote your channel, or take your place in a showcase, learn the rules that keep this realm running.</p>
    <p><small>Effective date: <strong>[October 20, 2026]</strong></small></p>
    <a class="button" href="#terms">ENTER THE CONTRACT ↓</a>
  </section>

  <main class="layout" id="terms">
    <aside class="sidebar">
      <h3>THE SACRED RULES</h3>
      <nav aria-label="Terms of Service navigation">
        <a href="#acceptance">01. Acceptance</a>
        <a href="#eligibility">02. Eligibility</a>
        <a href="#community">03. Community Conduct</a>
        <a href="#promotions">04. Promotions</a>
        <a href="#schedule">05. Scheduling</a>
        <a href="#content">06. Content & Rights</a>
        <a href="#safety">07. Safety & Enforcement</a>
        <a href="#third-party">08. Third-Party Services</a>
        <a href="#privacy">09. Privacy</a>
        <a href="#disclaimer">10. Disclaimers</a>
        <a href="#changes">11. Changes</a>
        <a href="#law">12. Governing Law</a>
        <a href="#contact">13. Contact</a>
      </nav>
    </aside>

    <article class="content">
      

      <section class="term" id="acceptance">
        <h2><span class="num">01.</span>Acceptance of Terms</h2>
        <p>These Terms of Service (“Terms”) apply to your use of Streamer Scheduler (“we,” “us,” or “our”), including our website, Discord community, streamer promotions, showcase sign-ups, schedules, and related services (collectively, the “Services”). By accessing or using the Services, you agree to these Terms and any clearly identified community rules or policies that apply. If you do not agree, do not use the Services.</p>
      </section>

      <section class="term" id="eligibility">
        <h2><span class="num">02.</span>Eligibility & Accounts</h2>
        <p>You must meet Discord’s minimum age requirements and any higher age requirement applicable to a particular channel, feature, or activity. You are responsible for your account, the accuracy of information you submit, and keeping your login credentials secure. Do not impersonate another person, misrepresent your channel, or use an account you are not authorized to control.</p>
        <p>Some activities may have additional eligibility rules, such as being an active streamer, meeting showcase requirements, or completing a sign-up correctly. Any special requirements should be clearly stated with the relevant activity.</p>
      </section>

      <section class="term" id="community">
        <h2><span class="num">03.</span>Community Conduct</h2>
        <p>Help keep the community welcoming, safe, and useful for creators. You agree not to:</p>
        <ul>
          <li>Harass, threaten, bully, stalk, or discriminate against other members.</li>
          <li>Spam, flood channels, evade moderation, or deliberately disrupt events.</li>
          <li>Share scams, malware, deceptive links, or content that violates applicable law.</li>
          <li>Impersonate creators, moderators, staff, or Streamer Scheduler.</li>
          <li>Manipulate sign-ups, falsely claim promotional activity, or interfere with another member’s scheduled slot.</li>
          <li>Promote content in channels or formats where it is not allowed, or ignore moderator instructions.</li>
        </ul>
        <p>Follow the current rules posted in our Discord server, including any channel-specific requirements. If a community rule conflicts with applicable law, the law takes precedence.</p>
      </section>

      <section class="term" id="promotions">
        <h2><span class="num">04.</span>Streamer Promotions & Showcases</h2>
        <p>Promotional opportunities, streamer showcases, live notifications, and advertising placements are provided subject to availability and the requirements announced for each event. A sign-up does not guarantee audience size, followers, subscriptions, revenue, raids, engagement, or growth.</p>
        <ul>
          <li>Submit accurate channel links, usernames, time-zone details, and other requested information.</li>
          <li>Only promote channels or content you are authorized to represent.</li>
          <li>Keep promotional posts relevant and follow the rules and limits of the designated channels.</li>
          <li>Do not promise or imply that Streamer Scheduler endorses a creator, channel, product, or service unless we explicitly confirm it.</li>
          <li>Respect other participants and do not sabotage, impersonate, or deliberately disrupt another creator’s slot.</li>
        </ul>
        <p>We may decline, remove, reschedule, or limit a promotion where reasonably necessary to enforce the rules, protect the community, address technical issues, or manage event capacity. Where practical, we will communicate material schedule changes through the designated announcement channel.</p>
      </section>

      <section class="term" id="schedule">
        <h2><span class="num">05.</span>Scheduling, Cancellations & Automation</h2>
        <p>Participants are responsible for checking their selected date, time, time zone, slot duration, and event instructions. Arrive prepared for your slot and notify the designated staff or channel as early as reasonably possible if you cannot participate.</p>
        <p>Automated posts, reminders, live alerts, or schedule updates may depend on Discord, Twitch, bots, integrations, permissions, network access, and third-party service availability. We do not guarantee that every notification will be delivered instantly or without error. If an automation fails, follow the current manual instructions provided by staff.</p>
        <p>We may adjust schedules to resolve conflicts, fill vacant slots, respond to outages, or keep an event running safely and fairly. Any fees, deposits, cancellation terms, or paid placements—if introduced—must be separately and clearly disclosed before purchase.</p>
      </section>

      <section class="term" id="content">
        <h2><span class="num">06.</span>Content, Branding & Permissions</h2>
        <p>You retain ownership of content you create and submit, subject to rights held by others. By posting promotional materials or providing content for an event, you give Streamer Scheduler permission to display, reproduce, and format that material as reasonably necessary to operate and promote the specific Services or event for which it was submitted. This permission is non-exclusive and does not transfer ownership to us. Remove or clarify this permission if your actual operations require different terms.</p>
        <p>You confirm that you have the rights and permissions needed to submit your usernames, logos, images, channel links, and promotional copy. Do not submit material that infringes another person’s intellectual property, privacy, or other rights. You may ask us to remove your submitted promotional material, subject to reasonable processing time and any legal or operational retention requirements.</p>
      </section>

      <section class="term" id="safety">
        <h2><span class="num">07.</span>Moderation, Reports & Enforcement</h2>
        <p>We may review reports and take proportionate action when we believe these Terms or community rules have been violated. Actions may include removing posts, correcting a schedule, issuing a warning, restricting promotional access, cancelling a slot, suspending participation, or removing a member from the community.</p>
        <p>Where appropriate, you may contact staff to ask for a moderation decision to be reviewed. We do not guarantee a particular review process or outcome. In urgent situations, we may act without advance notice to protect members, the Services, or an event. Nothing in this section prevents you from exercising rights available under applicable law.</p>
      </section>

      <section class="term" id="third-party">
        <h2><span class="num">08.</span>Third-Party Platforms</h2>
        <p>Streamer Scheduler may rely on Discord, Twitch, bots, scheduling tools, and other third-party services. Those services are operated independently and may have their own terms, privacy policies, eligibility requirements, outages, or restrictions. We are not responsible for third-party services we do not control. Your use of them is subject to their applicable terms.</p>
        <p>Streamer Scheduler is not affiliated with or endorsed by Discord or Twitch unless expressly stated. Their names and marks belong to their respective owners.</p>
      </section>

      <section class="term" id="privacy">
        <h2><span class="num">09.</span>Privacy & Information</h2>
        <p>We may receive information you choose to submit, such as your Discord username, streamer handle, channel URL, sign-up selections, and messages sent to staff. Information may also be processed by the platforms and bots used to operate the Services. We should use information only for legitimate community and service purposes, apply appropriate safeguards, and retain it only as reasonably necessary or as required by law.</p>
        <p>Read our Privacy Policy for more detail: <strong>[ADD PRIVACY POLICY URL OR REPLACE THIS TEXT WITH YOUR PRIVACY POLICY]</strong>. Before publishing, make sure the policy accurately describes the information your actual bots, integrations, and website collect, who can access it, and how users can request help with it.</p>
      </section>

      <section class="term" id="disclaimer">
        <h2><span class="num">10.</span>Disclaimers & Liability</h2>
        <p>The Services are provided on an “as available” basis to the extent permitted by law. We do not guarantee uninterrupted access, error-free automation, a particular number of viewers, promotional results, channel growth, or that every participant will attend a scheduled slot.</p>
        <p>To the extent permitted by applicable law, Streamer Scheduler is not responsible for indirect or consequential losses arising from your use of the Services. Nothing in these Terms excludes or limits liability, consumer rights, or remedies that cannot lawfully be excluded or limited. Have this section reviewed for the jurisdiction and service model that apply to you.</p>
      </section>

      <section class="term" id="changes">
        <h2><span class="num">11.</span>Changes & Availability</h2>
        <p>We may update the Services, event formats, schedules, rules, and these Terms as our operations change. We will post revised Terms here and update the effective date. Where required by law, we will provide notice or obtain consent before changes take effect. Continued use after updated Terms take effect indicates acceptance only to the extent permitted by applicable law.</p>
      </section>

      <section class="term" id="law">
        <h2><span class="num">12.</span>Governing Law</h2>
        <p>These Terms are governed by the laws of <strong>[INSERT STATE/COUNTRY]</strong>, without removing any mandatory consumer protections or rights that apply where you live. Replace this placeholder with the jurisdiction appropriate to the operator and the Services. Seek legal advice before adding any mandatory dispute-resolution or arbitration clause.</p>
      </section>

      <section class="term" id="contact">
        <h2><span class="num">13.</span>Contact the Keepers</h2>
        <p>Questions, concerns, or requests about these Terms can be sent to:</p>
        <p><strong>Streamer Scheduler</strong><br>
          Email: <a href="mailto:[YOUR-CONTACT-EMAIL]">bewdyreaper@gmail.com</a><br>
          Discord: <a href="[YOUR-DISCORD-INVITE-URL]">https://discord.gg/vkqNqw62vu</a>
        </p>
        <p>Replace the placeholders above with contact methods you actively monitor. Do not publish private contact information you do not want to make public.</p>
      </section>

      <div class="contact">
        <div class="sigil" aria-hidden="true">✦</div>
        <h2>Keep the Realm Running</h2>
        <p>Respect the schedule. Support your fellow creators. Keep the shadows free of chaos.</p>
        <a class="button" href="#top">RETURN TO THE TOP ↑</a>
      </div>
    </article>
  </main>

  <footer>
    <p><strong>STREAMER SCHEDULER</strong></p>
    <p>Terms of Service · Effective [October 20, 2026]</p>
    <p>Created for creators who thrive after dark.</p>
    <a class="back" href="#top">↑ Return to the surface</a>
  </footer>
</body>
</html>
