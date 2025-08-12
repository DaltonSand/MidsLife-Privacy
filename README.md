# MidsLife-Privacy
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MidsLife – Privacy Policy</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif; margin: 40px; line-height: 1.6; color: #111; max-width: 900px; }
    h1, h2, h3 { color: #00205B; }
    code, pre { background: #f6f8fa; padding: 2px 6px; border-radius: 4px; }
    .muted { color: #555; }
    .box { background: #fafbff; border: 1px solid #e6e9f2; border-radius: 8px; padding: 16px; }
    table { border-collapse: collapse; width: 100%; margin: 12px 0; font-size: 0.96rem; }
    th, td { border: 1px solid #e6e9f2; padding: 8px; vertical-align: top; }
    th { background: #f1f3f8; text-align: left; }
    a { color: #0b63ff; text-decoration: none; }
    a:hover { text-decoration: underline; }
    .toc a { display: block; margin: 4px 0; }
    small { color: #666; }
  </style>
</head>
<body>
  <h1>MidsLife – Privacy Policy</h1>
  <p><strong>Effective date:</strong> August 12, 2025</p>
  <p class="box"><strong>Independence & Non‑Affiliation.</strong> MidsLife is independently developed and is <strong>not affiliated with, sponsored by, or endorsed by</strong> the United States Naval Academy, the U.S. Navy, or the Department of Defense. For official information, use official USNA channels.</p>

  <h2>At a Glance</h2>
  <ul>
    <li>We collect only what’s needed to create your account and provide features (e.g., workout logs).</li>
    <li>Data is stored in <strong>Google Firebase</strong> (authentication, database, storage). TLS in transit; encryption at rest.</li>
    <li>We <strong>do not sell</strong> your data and we <strong>do not share</strong> it for cross‑app advertising or tracking.</li>
    <li>You can request account and data deletion any time at <a href="mailto:support@midslife.app">support@midslife.app</a>.</li>
  </ul>

  <h2>Table of Contents</h2>
  <div class="toc">
    <a href="#scope">1. Scope</a>
    <a href="#data-we-collect">2. Data We Collect</a>
    <a href="#sources">3. Sources of Data</a>
    <a href="#how-we-use">4. How We Use Data</a>
    <a href="#permissions">5. Device Permissions</a>
    <a href="#sharing">6. Sharing & Disclosure</a>
    <a href="#retention">7. Retention</a>
    <a href="#security">8. Security</a>
    <a href="#transfers">9. International Data Transfers</a>
    <a href="#your-rights">10. Your Choices & Rights</a>
    <a href="#children">11. Children’s Privacy</a>
    <a href="#changes">12. Changes to This Policy</a>
    <a href="#contact">13. Contact</a>
    <a href="#apple-summary">Appendix A – Apple App Privacy Summary</a>
    <a href="#subprocessors">Appendix B – Subprocessors & Links</a>
  </div>

  <h2 id="scope">1. Scope</h2>
  <p>This policy describes how MidsLife (“we,” “us,” “our”) collects, uses, shares, and protects information when you use the MidsLife mobile application and related websites (collectively, the “Service”).</p>

  <h2 id="data-we-collect">2. Data We Collect</h2>
  <h3>2.1 Account & Profile</h3>
  <ul>
    <li><strong>Email address</strong> (used for sign‑in), name (if provided), profile photo (if uploaded).</li>
    <li><strong>App‑assigned identifiers</strong> (e.g., Firebase UID), creation timestamps.</li>
    <li>Optional profile attributes: <em>company, class year (derived), alpha, group selection</em>.</li>
  </ul>

  <h3>2.2 User Content</h3>
  <ul>
    <li>Workout/STEEL logs (type, intensity, timestamp, notes; and an <code>isAuthenticated</code> flag if used by PMOs).</li>
    <li>Group participation info (selected group, attendance plans/status if you choose to use those features).</li>
    <li>Images you choose to upload (e.g., workout photo). Photos are never uploaded without your action.</li>
  </ul>

  <h3>2.3 Usage, Diagnostics, and Device Information</h3>
  <ul>
    <li>Basic app usage events (e.g., screens visited) if <strong>Firebase Analytics</strong> is enabled.</li>
    <li>Crash logs and performance data via <strong>Firebase Crashlytics</strong> (e.g., device model, OS version, anonymized session info).</li>
    <li>IP address and general region (collected by Firebase infrastructure for security/anti‑abuse).</li>
  </ul>

  <h3>2.4 Location</h3>
  <p>MidsLife does <strong>not</strong> collect precise location by default. If we ever offer a location‑based feature (e.g., weather near you) that requires permission, the app will explicitly ask, and you can decline. You can update location permissions in your device settings at any time.</p>

  <h3>2.5 Payments</h3>
  <p>MidsLife currently does <strong>not</strong> process in‑app purchases. If this changes, we will update this policy and identify any payment processors used.</p>

  <h2 id="sources">3. Sources of Data</h2>
  <ul>
    <li><strong>You</strong> – information you provide directly (sign‑in, logs, profile, uploads).</li>
    <li><strong>Your device/app</strong> – usage/diagnostics collected by Firebase SDKs.</li>
    <li><strong>Third‑party content you access</strong> – if you open documents/links hosted by third parties (e.g., publicly available training documents), those sites may collect data per their own policies.</li>
  </ul>

  <h2 id="how-we-use">4. How We Use Data</h2>
  <ul>
    <li><strong>App functionality:</strong> authenticate users, save and display logs, manage groups, load documents.</li>
    <li><strong>Performance & safety:</strong> secure access (Auth), prevent abuse, diagnose crashes, improve reliability.</li>
    <li><strong>Experience improvements:</strong> understand feature usage (if Analytics enabled) to prioritize updates.</li>
    <li><strong>Support:</strong> respond to bug reports and user requests.</li>
  </ul>
  <p>We do <strong>not</strong> use your data for cross‑app advertising or third‑party marketing.</p>

  <h2 id="permissions">5. Device Permissions</h2>
  <table>
    <tr><th>Permission</th><th>Purpose</th><th>When Requested</th></tr>
    <tr><td>Photos / Media</td><td>Let you attach a photo to a workout log.</td><td>Only when you tap “Upload/Choose Photo.”</td></tr>
    <tr><td>Camera (optional)</td><td>Take a new photo to attach.</td><td>Only when you tap “Camera.”</td></tr>
    <tr><td>Notifications (optional)</td><td>Reminders/updates (if enabled).</td><td>When you opt in to notifications.</td></tr>
    <tr><td>Location (optional)</td><td>If a feature needs your approximate location (e.g., weather), and only if you opt in.</td><td>Only if you enable that feature.</td></tr>
  </table>

  <h2 id="sharing">6. Sharing & Disclosure</h2>
  <p>We do <strong>not</strong> sell your personal data, and we do <strong>not</strong> share it for tracking across other companies’ apps and websites.</p>
  <h3>6.1 Service Providers (Processors)</h3>
  <p>We use third‑party providers to operate the Service. They process data on our behalf under contractual terms:</p>
  <ul>
    <li><strong>Google Firebase</strong> – Authentication, Firestore (database), Storage (files), Crashlytics, (optional) Analytics, Remote Config.</li>
    <li><strong>Apple</strong> – Push notifications/APNs; Sign in with Apple (if offered).</li>
  </ul>
  <h3>6.2 Legal Requirements</h3>
  <p>We may disclose information if required by law or in good faith belief that such action is necessary to comply with legal obligations, protect rights or safety, or investigate potential violations.</p>

  <h2 id="retention">7. Retention</h2>
  <ul>
    <li><strong>Account data</strong> (email, UID, profile): retained while your account is active.</li>
    <li><strong>User content</strong> (logs, images): retained until you delete it or delete your account.</li>
    <li><strong>Backups</strong>: may persist for up to 30–90 days in provider backups after deletion.</li>
  </ul>
  <p>You may request deletion any time (see <a href="#your-rights">Your Rights</a>).</p>

  <h2 id="security">8. Security</h2>
  <ul>
    <li><strong>Transport & storage:</strong> TLS in transit; encryption at rest in Firebase.</li>
    <li><strong>Access control:</strong> Firebase Security Rules limit access to your data to you and authorized roles (e.g., designated PMOs for STEEL oversight where applicable).</li>
    <li><strong>Least privilege:</strong> administrative access is restricted and audited.</li>
    <li><strong>App encryption:</strong> the app relies on Apple and Firebase encryption; no proprietary cryptography is shipped.</li>
  </ul>

  <h2 id="transfers">9. International Data Transfers</h2>
  <p>Data is primarily processed in the United States. Providers may replicate or process data in other regions to ensure reliability and performance, subject to their compliance frameworks.</p>

  <h2 id="your-rights">10. Your Choices & Rights</h2>
  <ul>
    <li><strong>Access & correction:</strong> you may view and edit profile details in‑app.</li>
    <li><strong>Deletion:</strong> request account/data deletion by emailing <a href="mailto:support@midslife.app">support@midslife.app</a>. We complete verified deletions within 30 days, subject to lawful retention.</li>
    <li><strong>Opt‑outs:</strong> you can disable Analytics (if toggles are provided) and revoke permissions (Camera, Photos, Location, Notifications) in device settings.</li>
  </ul>
  <p class="muted"><em>Regional rights (e.g., GDPR/CCPA). </em>Regardless of your location, we honor reasonable requests to access or delete personal data. If you are in a jurisdiction with specific rights, contact us and we’ll assist consistent with applicable law.</p>

  <h2 id="children">11. Children’s Privacy</h2>
  <p>MidsLife is intended for adult users in higher education and is <strong>not</strong> directed to children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided personal information, contact us to request deletion.</p>

  <h2 id="changes">12. Changes to This Policy</h2>
  <p>We may update this policy to reflect changes to the Service or legal requirements. Material changes will be highlighted here with a new effective date.</p>

  <h2 id="contact">13. Contact</h2>
  <p>Email: <a href="mailto:support@midslife.app">support@midslife.app</a></p>
  <p>Mail: MidsLife – Privacy, 121 Blake Rd, Annapolis, MD 21402 (or your preferred mailing address)</p>

  <h2 id="apple-summary">Appendix A – Apple App Privacy Summary (Mapping)</h2>
  <table>
    <tr>
      <th>Apple Category</th>
      <th>Data Elements</th>
      <th>Linked to You</th>
      <th>Used For</th>
      <th>Tracking?</th>
    </tr>
    <tr>
      <td>Contact Info</td>
      <td>Email address</td>
      <td>Yes</td>
      <td>App functionality (sign‑in), support</td>
      <td>No</td>
    </tr>
    <tr>
      <td>Identifiers</td>
      <td>User ID (Firebase UID), Instance IDs</td>
      <td>Yes</td>
      <td>App functionality, security</td>
      <td>No</td>
    </tr>
    <tr>
      <td>User Content</td>
      <td>Workout logs, notes, profile photo</td>
      <td>Yes</td>
      <td>App functionality</td>
      <td>No</td>
    </tr>
    <tr>
      <td>Usage Data</td>
      <td>App interactions, diagnostics (Crashlytics)</td>
      <td>No (aggregated)</td>
      <td>Analytics (optional), app performance</td>
      <td>No</td>
    </tr>
    <tr>
      <td>Location (optional)</td>
      <td>Approximate location (if feature enabled)</td>
      <td>No</td>
      <td>Feature functionality (e.g., weather)</td>
      <td>No</td>
    </tr>
  </table>
  <p class="muted">We do not sell data, and we do not share data for cross‑app advertising (“tracking”).</p>

  <h2 id="subprocessors">Appendix B – Subprocessors & Policies</h2>
  <ul>
    <li><strong>Google Firebase</strong> (Auth, Firestore, Storage, Crashlytics, Remote Config, optional Analytics) – <a href="https://firebase.google.com/support/privacy" target="_blank" rel="noopener">Privacy & Security</a></li>
    <li><strong>Google Cloud</strong> (underlying infrastructure for Firebase) – <a href="https://cloud.google.com/security/privacy" target="_blank" rel="noopener">Privacy</a></li>
    <li><strong>Apple</strong> (APNs, Sign in with Apple) – <a href="https://www.apple.com/legal/privacy/" target="_blank" rel="noopener">Privacy</a></li>
  </ul>

  <hr />
  <small>© 2025 MidsLife. All rights reserved.</small>
</body>
</html>
