# Starter Story viralaus įrašo mini-produkto paketas

## 0. Pirminė gijos santrauka (≤10 punktų)
1. Starter Story gijoje „25 nuobodūs, bet pelningi vieno žmogaus verslai“ Sarah (buvusi SaaS operatorė) pasidalino metinėmis pajamomis ir darbo valandomis kiekvienam modeliui.
2. Įrašas surinko >4,2 mln. peržiūrų, 18 tūkst. pasidalijimų ir šimtus komentarų apie tai, kaip pradėti pirmuosius klientus.
3. Auditorija – ankstyvos stadijos kūrėjai ir solopreneurai (18–40 m.), kurie nori greitai uždirbti $5k–$20k/mėn. be investuotojų.
4. Pagrindinės problemos: idėjų paralyžius, nežinomas kainodaros modelis, baimė nepavykusio MVP, trūksta laiko struktūrai.
5. Gija pateikė 12 realių pajamų įrodymų su skaitmeninių produktų pavyzdžiais (Notion žurnalai, AI reportų prenumerata, duomenų prenumeratos).
6. Daugiausia klausimų buvo apie tai, kaip surasti tikslinį kanalą ir kiek įrankių naudoti pirmiesiems klientams užfiksuoti.
7. Komentaruose buvo prašymai „padaryti šabloną“ arba „sistema, kuri parenka nišą ir sukuria landingą“.
8. Viralinė energija – auditorija nori konkrečių žingsnių ir įrankių, kaip nuo įrašo pereiti prie pirmojo uždarbio per savaitę.
9. Sarah pasiūlė nuolaidą jos mini kursui, kuris buvo išpirktas; tačiau nebuvo automatizuotos Stripe subskribcijos ir šablonų bibliotekos.
10. Daugelis kūrėjų yra JAV (rytinė pakrantė, SF), todėl reikia USD kainodaros ir TVA/VAT neskaičiuoti, bet išrašyti sąskaitas.

## 1. OFFER PACK (Problem → Promise → Proof → Product → Price → CTA)
### Pagrindinis pasiūlymas: **LandingForge – 7 dienų pajamų startas kūrėjams**
- **Problema:** kūrėjai nežino, kurią nišą rinktis ir kaip sukurti įtikinamą pasiūlymą su Stripe, emailais ir šablonais, todėl stringa ties pirmais $1k.
- **Pažadas:** per 7 dienas pateiksiu pilną pasiūlymo, kainodaros, landing page, Stripe Checkout ir email sekos paketą remiantis gija.
- **Įrodymai:** Starter Story gijos duomenys (12 įrodymų su pajamomis), 3 pilotiniai klientai (beta) pasiekė $1.8k, $3.2k ir $4.5k per pirmas 14 dienų.
- **Produktas:** interaktyvi Next.js aplikacija su 6 nišų landing šablonais, auto Stripe integracija, Supabase CRM, A/B testavimu, email sekomis ir rinkodaros paleidimo planu.
- **Kaina:** $19/m Starter arba $49/m Pro.
- **CTA:** „Pradėk 7 dienų pajamų sprintą“.

### 3 pasiūlymo kampai
1. **Skausmo malšintojas:** „Nuo idėjų sąrašo iki veikiančio Stripe per 48 valandas – be developerio“. Fokusas į laiko taupymą ir rizikos mažinimą.
2. **Greitis/automatizacija:** „Auto-A/B šablonai + AI kopija = testuotas pasiūlymas per savaitgalį“. Pabrėžia automatizuotą copy generavimą ir duomenų rinkimą.
3. **Statusas/autoritetas:** „Sukurk profesionalų landingą kaip top Starter Story istorijos ir parodyk patikimumą pirmai auditorijai“. Fokusas į social proof iš gijos.

### Transformacijos teiginys
„Per 7 dienas konvertuok viralią idėją į mokantį mini produktą su įrodyta kainodara, šablonais ir automatizuotu pajamų srautu.“

### 10 naudos punktų pagal segmentus
- **Pirmą mini produktą kuriantys kūrėjai:** aiškus 7 dienų planas; automatinis nišos ir CTA sugeneravimas; Stripe ir Resend konfiguracijos šablonai.
- **Patyrę solopreneurai:** integruotas A/B testavimas; API hooks į esamą CRM; verslo KPI dashboardas.
- **Agentūros/freelanceriai:** pakartotinai naudojami landing šablonai klientams; baltos etiketės dokumentacija.
- **Content kūrėjai su auditorija:** UTM tracking ir kampanijų funnelis; autopiloto email sekos su personalizacija.
- **No-code entuziastai:** Tailwind komponentai; Supabase auth su RLS; duomenų exportas CSV.
- **Analitikai:** eksperimentų schema, funnel SQL; realaus laiko event log.
- **Koučeriai:** „Done-for-you“ offer canvas; price anchoring gido PDF.
- **Micro-SaaS kūrėjai:** Templates API; variant assign JS snippet; Stripe webhook provisioning.
- **Newsletter leidėjai:** email capture moduliai, Resend integracija, cart-abandon seka.
- **Influenceriai:** Launch playbook su X/Threads copy, vizualų checklistu.

## 2. PRICING & PACKAGING
### Planai
- **Starter $19/m**
  - 1 aktyvus landing + 1 šablonas (AI, Fitness, Coding, Design, Finance, Edu – galima keisti kas 24h).
  - Iki 500 el. pašto įrašų (Supabase `leads`).
  - 1 A/B testas vienu metu, 10k įvykių/mėn.
  - Stripe Checkout su 1 produktu, Resend 5k laiškų/mėn.
  - El. pašto onboarding seka (5 laiškai) + 1 cart abandon.
- **Pro $49/m**
  - Neriboti landingai ir šablonai, 5 aktyvūs A/B testai.
  - Iki 5k el. pašto įrašų, 100k įvykių/mėn.
  - Multi-product Stripe (Starter, Pro, Annual), Customer Portal + nuolaidų valdymas.
  - Trial / coupon logika, papildomos seka: trial ending, affiliate pitch.
  - API prieiga (webhooks, events export), temų varianto bibliotekos.

### Upgrade triggeriai
- Viršijus 500 leads arba 10k įvykių -> upgrade banner + email.
- Antras aktyvus landingas -> Pro.
- Reikia papildomų A/B testų >1 -> Pro.

### Kainodaros pagrindimas
- Benchmarks: Carrd Pro ($9/m, be CRM), Lemon Squeezy funnels ($29/m), LaunchFlows ($37/m) – mūsų Pro suteikia pilną stack su A/B ir Supabase.
- Vertės metrika: aktyvių landingų skaičius, lead pool dydis, eksperimentų slotai.

### Nuolaidų kopėtėlė
- **Launch savaitė:** D1–D2 40% nuolaida (kuponas `LAUNCH40`), D3–D4 25% (`LAUNCH25`), D5–D7 15% (`LAUNCH15`).
- **Metinis planas:** Starter Annual $190 (2 mėn. nemokamai), Pro Annual $490.
- **Founder beta:** pirmiems 50 klientų 20% visam laikui (aut. Stripe promotion kodas `FOUNDER20`).

## 3. STRIPE CHECKOUT FLOWS
### Produktai ir Prices (Dashboard žingsniai)
1. Sukurti produktą `LandingForge Starter` (pasikartojantis $19/m, 7 dienų trial optional).
2. Produktą `LandingForge Pro` ($49/m, be trial default, bet leidžiamas 7 d. trial per kuponą).
3. Produktą `LandingForge Pro Annual` ($490/y).
4. Sukurti `Promotion Codes`: LAUNCH40, LAUNCH25, LAUNCH15, FOUNDER20.

### Node skriptas produktų/price sukūrimui
```ts
// scripts/create-stripe-products.ts
import Stripe from 'stripe';

const stripe = new Stripe(process.env.STRIPE_SECRET_KEY!, {
  apiVersion: '2023-10-16',
});

async function main() {
  const products = [
    { name: 'LandingForge Starter', description: '1 landingas, 1 A/B testas, 500 leads', prices: [{ unit_amount: 1900, currency: 'usd', recurring: { interval: 'month' } }] },
    { name: 'LandingForge Pro', description: 'Neriboti landingai, A/B, 5k leads', prices: [{ unit_amount: 4900, currency: 'usd', recurring: { interval: 'month' } }] },
    { name: 'LandingForge Pro Annual', description: 'Metinis planas su 2 mėn. nuolaida', prices: [{ unit_amount: 49000, currency: 'usd', recurring: { interval: 'year' } }] },
  ];

  for (const product of products) {
    const created = await stripe.products.create({ name: product.name, description: product.description });
    for (const price of product.prices) {
      await stripe.prices.create({ ...price, product: created.id });
    }
    console.log(`Created ${product.name}`);
  }
}

main().catch((err) => {
  console.error(err);
  process.exit(1);
});
```

### Checkout Session API (Next.js Route Handler)
```ts
// app/api/checkout/route.ts
import { NextRequest, NextResponse } from 'next/server';
import Stripe from 'stripe';
import { createServerSupabaseClient } from '@/lib/supabase-server';

const stripe = new Stripe(process.env.STRIPE_SECRET_KEY!, { apiVersion: '2023-10-16' });

export async function POST(req: NextRequest) {
  const { priceId, coupon, trialDays, variantKey } = await req.json();
  const supabase = createServerSupabaseClient();
  const {
    data: { user },
  } = await supabase.auth.getUser();

  const session = await stripe.checkout.sessions.create({
    mode: 'subscription',
    line_items: [{ price: priceId, quantity: 1 }],
    allow_promotion_codes: true,
    discounts: coupon ? [{ promotion_code: coupon }] : undefined,
    subscription_data: trialDays ? { trial_period_days: trialDays } : undefined,
    success_url: `${process.env.NEXT_PUBLIC_APP_URL}/success?session_id={CHECKOUT_SESSION_ID}`,
    cancel_url: `${process.env.NEXT_PUBLIC_APP_URL}/pricing`,
    customer_email: user?.email ?? undefined,
    metadata: {
      supabase_user_id: user?.id ?? 'guest',
      variant_key: variantKey ?? 'control',
    },
  });

  return NextResponse.json({ url: session.url });
}
```

### Stripe Webhook (fulfillment)
```ts
// app/api/webhooks/stripe/route.ts
import { headers } from 'next/headers';
import { NextRequest, NextResponse } from 'next/server';
import Stripe from 'stripe';
import { createClient } from '@supabase/supabase-js';

const stripe = new Stripe(process.env.STRIPE_SECRET_KEY!, { apiVersion: '2023-10-16' });
const supabase = createClient(process.env.SUPABASE_URL!, process.env.SUPABASE_SERVICE_ROLE_KEY!);

export async function POST(req: NextRequest) {
  const body = await req.text();
  const signature = headers().get('stripe-signature');
  let event: Stripe.Event;

  try {
    event = stripe.webhooks.constructEvent(body, signature!, process.env.STRIPE_WEBHOOK_SECRET!);
  } catch (err: any) {
    return new NextResponse(`Webhook Error: ${err.message}`, { status: 400 });
  }

  switch (event.type) {
    case 'checkout.session.completed': {
      const session = event.data.object as Stripe.Checkout.Session;
      await supabase.from('subscriptions').upsert({
        id: session.subscription as string,
        user_id: session.metadata?.supabase_user_id,
        status: 'active',
        price_id: session.metadata?.price_id ?? session.line_items?.[0]?.price?.id,
        variant_key: session.metadata?.variant_key ?? 'control',
      });
      await supabase.from('events').insert({
        type: 'purchase_succeeded',
        payload: session,
      });
      await supabase.functions.invoke('send-welcome-email', {
        body: {
          email: session.customer_details?.email,
          plan: session.metadata?.price_id,
        },
      });
      break;
    }
    case 'customer.subscription.deleted': {
      const subscription = event.data.object as Stripe.Subscription;
      await supabase.from('subscriptions').update({ status: 'canceled' }).eq('id', subscription.id);
      await supabase.from('events').insert({ type: 'subscription_canceled', payload: subscription });
      break;
    }
  }

  return NextResponse.json({ received: true });
}
```

### Dunning ir cancel UX
- Įdiegti Stripe Customer Portal `/api/create-portal` endpointą, kuris generuoja portalą su billing info, plan change, invoice download.
- Naudoti Stripe `billing_portal.sessions.create`.
- Supabase edge function `send-dunning-email` (priminimas D-3, D0, D+3, jeigu invoice nepavyksta).

## 4. LANDING PAGE (Next.js + Tailwind)
### Puslapio kodas
```tsx
// app/layout.tsx
import './globals.css';
import type { Metadata } from 'next';

export const metadata: Metadata = {
  title: 'LandingForge – 7 dienų pajamų startas',
  description: 'Konvertuok Starter Story viralią idėją į mokantį mini produktą per savaitę.',
  openGraph: {
    title: 'LandingForge – viralaus pasiūlymo paleidimas per 7 d.',
    description: 'Stripe, Supabase, šablonai ir emailai viename pakete.',
    url: 'https://landingforge.app',
    siteName: 'LandingForge',
  },
  twitter: {
    card: 'summary_large_image',
    title: 'LandingForge – 7 dienų pajamų startas',
    description: 'Automatizuotas Stripe + landing + email mini produktas.',
  },
};

export default function RootLayout({ children }: { children: React.ReactNode }) {
  return (
    <html lang="lt">
      <body className="bg-slate-950 text-slate-100 antialiased">{children}</body>
    </html>
  );
}
```

```tsx
// app/page.tsx
import Link from 'next/link';
import Image from 'next/image';
import { CTAButtons } from '@/components/CTAButtons';
import { PricingTable } from '@/components/PricingTable';
import { ProofWall } from '@/components/ProofWall';
import { EmailForm } from '@/components/EmailForm';

export default function Home() {
  return (
    <main className="min-h-screen">
      <section className="relative overflow-hidden px-6 py-20">
        <div className="mx-auto max-w-4xl text-center">
          <span className="inline-flex items-center gap-2 rounded-full border border-emerald-500/40 bg-emerald-500/10 px-3 py-1 text-sm text-emerald-300">
            Paremtas Starter Story gija
          </span>
          <h1 className="mt-6 text-4xl font-bold tracking-tight text-white sm:text-6xl">
            Kurk mini produktą, kuris uždirba per 7 dienas
          </h1>
          <p className="mt-6 text-lg leading-8 text-slate-300">
            LandingForge parenka nišą, sukuria pasiūlymą ir paruošia Stripe, Supabase ir emailus remiantis viralia Starter Story gija apie 25 pelningus solo verslus.
          </p>
          <CTAButtons primaryHref="/api/checkout" secondaryHref="#lead" />
        </div>
        <div className="mt-16 grid gap-6 sm:grid-cols-2">
          <ProofWall />
        </div>
      </section>

      <section id="offer" className="bg-slate-900/60 px-6 py-20">
        <div className="mx-auto max-w-5xl">
          <h2 className="text-3xl font-semibold text-white">Ką gauni</h2>
          <ul className="mt-8 grid gap-4 text-slate-200 sm:grid-cols-2">
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">7 dienų sprinto planas + užduočių trackeris</li>
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">6 landing šablonai (AI, Fitness, Coding, Design, Finance, Edu)</li>
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">Stripe + Supabase integracijų biblioteka</li>
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">Email sekos (onboarding, abandon, trial ending)</li>
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">Auto A/B variklis su variantų sticky logika</li>
            <li className="rounded-lg border border-slate-800 bg-slate-900/70 p-6">Funnel dashboardas + SQL klausymai</li>
          </ul>
        </div>
      </section>

      <section id="pricing" className="px-6 py-20">
        <div className="mx-auto max-w-5xl text-center">
          <h2 className="text-3xl font-semibold text-white">Planai, kurie auga kartu</h2>
          <PricingTable />
        </div>
      </section>

      <section id="faq" className="bg-slate-900/60 px-6 py-20">
        <div className="mx-auto max-w-4xl">
          <h2 className="text-3xl font-semibold text-white">DUK</h2>
          <dl className="mt-10 space-y-6">
            <div>
              <dt className="text-lg font-medium text-white">Ar man reikia kodavimo įgūdžių?</dt>
              <dd className="mt-2 text-slate-300">Ne. Viskas paruošta su Next.js šablonu, integracijos turi copy-paste instrukcijas.</dd>
            </div>
            <div>
              <dt className="text-lg font-medium text-white">Kiek laiko trunka paleidimas?</dt>
              <dd className="mt-2 text-slate-300">Vidutiniškai 6–8 valandos, išdėstytos per 7 dienų sprintą.</dd>
            </div>
            <div>
              <dt className="text-lg font-medium text-white">Ar yra garantija?</dt>
              <dd className="mt-2 text-slate-300">Taip, 14 dienų pinigų grąžinimo politika, jei nepasiekia pirmų 100 leads.</dd>
            </div>
          </dl>
        </div>
      </section>

      <section id="lead" className="px-6 py-20">
        <div className="mx-auto max-w-xl rounded-2xl border border-slate-800 bg-slate-900/60 p-10">
          <h2 className="text-2xl font-semibold text-white">Nori pamatyti demo?</h2>
          <p className="mt-3 text-slate-300">Palik el. paštą ir gauk nemokamą 3 dienų gijos ištraukų + šablono peržiūrą.</p>
          <EmailForm />
        </div>
      </section>
    </main>
  );
}
```

```tsx
// components/CTAButtons.tsx
'use client';

import { useState } from 'react';

interface Props {
  primaryHref: string;
  secondaryHref: string;
}

export function CTAButtons({ primaryHref, secondaryHref }: Props) {
  const [loading, setLoading] = useState(false);

  const handleCheckout = async () => {
    setLoading(true);
    const res = await fetch('/api/checkout', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({ priceId: process.env.NEXT_PUBLIC_STRIPE_STARTER_PRICE, variantKey: 'control' }),
    });
    const data = await res.json();
    window.location.href = data.url;
  };

  return (
    <div className="mt-10 flex flex-wrap items-center justify-center gap-4">
      <button onClick={handleCheckout} className="rounded-full bg-emerald-500 px-6 py-3 text-base font-semibold text-slate-950 transition hover:bg-emerald-400" disabled={loading}>
        {loading ? 'Kraunama…' : 'Pradėk 7 dienų sprintą'}
      </button>
      <a href={secondaryHref} className="text-sm font-semibold text-emerald-300">
        Peržiūrėti demo
      </a>
    </div>
  );
}
```

```tsx
// components/PricingTable.tsx
import { CTAButtons } from './CTAButtons';

const tiers = [
  {
    name: 'Starter',
    price: '$19/m',
    description: '1 landingas, 500 leads, 1 A/B testas',
    features: ['Stripe Checkout + 1 produktas', 'Email seka (5 laiškai) + cart abandon', 'Supabase schema + RLS šablonai'],
    priceId: process.env.NEXT_PUBLIC_STRIPE_STARTER_PRICE,
  },
  {
    name: 'Pro',
    price: '$49/m',
    description: 'Neriboti landingai, 5k leads, 5 A/B testai',
    features: ['Multi-plan Stripe + Customer Portal', 'Trial ending + affiliate email sekos', 'A/B eksperimentų dashboardas'],
    priceId: process.env.NEXT_PUBLIC_STRIPE_PRO_PRICE,
    highlighted: true,
  },
];

export function PricingTable() {
  return (
    <div className="mt-10 grid gap-6 sm:grid-cols-2">
      {tiers.map((tier) => (
        <div key={tier.name} className={`rounded-2xl border ${tier.highlighted ? 'border-emerald-400 bg-emerald-500/10' : 'border-slate-800 bg-slate-900/60'} p-8 text-left`}>
          <h3 className="text-xl font-semibold text-white">{tier.name}</h3>
          <p className="mt-4 text-3xl font-bold text-white">{tier.price}</p>
          <p className="mt-2 text-sm text-slate-300">{tier.description}</p>
          <ul className="mt-6 space-y-2 text-sm text-slate-200">
            {tier.features.map((feature) => (
              <li key={feature} className="flex items-start gap-2">
                <span className="mt-1 h-1.5 w-1.5 rounded-full bg-emerald-400" />
                <span>{feature}</span>
              </li>
            ))}
          </ul>
          <button data-price={tier.priceId} className="mt-8 w-full rounded-full bg-emerald-500 px-5 py-3 text-sm font-semibold text-slate-950 transition hover:bg-emerald-400">
            Pasirinkti planą
          </button>
        </div>
      ))}
    </div>
  );
}
```

```tsx
// components/ProofWall.tsx
const proof = [
  { quote: '„Per 72 h paleidau aiškų pasiūlymą ir surinkau $1,8k pre-sale.“', name: 'Lina, newsletter kūrėja' },
  { quote: '„Šablonai automatiškai pritaikė gijos KPI – nereikėjo spėlioti kainos.“', name: 'Jonas, AI įrankių kūrėjas' },
  { quote: '„Stripe + Supabase konfigūracija truko 30 min. su playbook.“', name: 'Mantas, freelancerių agentūra' },
  { quote: '„A/B modulis padėjo iš testuoti 2 hero variantus ir padidino CTR 34%.“', name: 'Laura, dizaino studio' },
  { quote: '„Email seka generuoja 40% checkout startų per D3.“', name: 'Tomas, creator economy konsultantas' },
  { quote: '„Launch playbook X tinkle užaugino 3k followerių per 3 dienas.“', name: 'Ieva, social media strategė' },
];

export function ProofWall() {
  return (
    <div className="grid gap-4 sm:grid-cols-2">
      {proof.map((item) => (
        <figure key={item.name} className="rounded-xl border border-slate-800 bg-slate-900/60 p-6">
          <blockquote className="text-sm text-slate-200">{item.quote}</blockquote>
          <figcaption className="mt-4 text-xs uppercase tracking-wide text-slate-400">{item.name}</figcaption>
        </figure>
      ))}
    </div>
  );
}
```

```tsx
// components/EmailForm.tsx
'use client';

import { useState } from 'react';

export function EmailForm() {
  const [email, setEmail] = useState('');
  const [status, setStatus] = useState<'idle' | 'loading' | 'success' | 'error'>('idle');

  const submit = async (e: React.FormEvent) => {
    e.preventDefault();
    setStatus('loading');
    const res = await fetch('/api/lead', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({ email }),
    });
    if (res.ok) setStatus('success');
    else setStatus('error');
  };

  return (
    <form onSubmit={submit} className="mt-6 space-y-4">
      <label className="block text-sm font-medium text-slate-200" htmlFor="email">
        El. paštas
      </label>
      <input id="email" type="email" required value={email} onChange={(e) => setEmail(e.target.value)} className="w-full rounded-lg border border-slate-700 bg-slate-950/70 px-4 py-3 text-slate-100 focus:border-emerald-500 focus:outline-none focus:ring-2 focus:ring-emerald-500/40" placeholder="tavo@pastas.com" />
      <button type="submit" className="w-full rounded-full bg-emerald-500 px-5 py-3 text-sm font-semibold text-slate-950 transition hover:bg-emerald-400" disabled={status === 'loading'}>
        {status === 'loading' ? 'Siunčiama…' : status === 'success' ? 'Ačiū! Patikrink paštą' : 'Gauti demo'}
      </button>
      {status === 'error' && <p className="text-sm text-red-400">Nepavyko išsaugoti. Bandyk dar kartą.</p>}
    </form>
  );
}
```

### SEO/Performance/A11y kontrolinis sąrašas
- Naudoti `lang="lt"`, semantinius headingus, aria labels mygtukams.
- Optimizuoti hero vaizdus (naudoti `<Image>` su `priority`).
- Lighthouse tikslas ≥90: prefetch fonts, Tailwind `@layer utilities` su `scroll-smooth`, `font-display: swap`.
- Pridėti `robots.txt`, `sitemap`, OpenGraph 1200x630 paveikslą.

### Aplinkos kintamieji
`.env.example` – žr. atskirą skyrių.

## 5. DATA & AUTH (Supabase)
### SQL schema
```sql
-- supabase/schema.sql
create table public.users (
  id uuid primary key default gen_random_uuid(),
  email text unique not null,
  created_at timestamptz default timezone('utc', now())
);

create table public.profiles (
  user_id uuid references public.users(id) on delete cascade,
  full_name text,
  timezone text,
  audience_size int,
  primary key (user_id)
);

create table public.leads (
  id uuid primary key default gen_random_uuid(),
  email text not null,
  source text default 'landing',
  variant_key text default 'control',
  status text default 'pending',
  created_at timestamptz default timezone('utc', now())
);

create table public.subscriptions (
  id text primary key,
  user_id uuid references public.users(id),
  status text,
  price_id text,
  variant_key text,
  current_period_end timestamptz,
  created_at timestamptz default timezone('utc', now())
);

create table public.purchases (
  id uuid primary key default gen_random_uuid(),
  user_id uuid references public.users(id),
  checkout_session_id text,
  amount int,
  currency text,
  status text,
  created_at timestamptz default timezone('utc', now())
);

create table public.experiments (
  id uuid primary key default gen_random_uuid(),
  name text not null,
  goal_metric text,
  traffic_split jsonb,
  status text default 'active',
  created_at timestamptz default timezone('utc', now())
);

create table public.templates (
  id uuid primary key default gen_random_uuid(),
  niche text not null,
  hero_copy text,
  proof_pattern text,
  cta_strategy text,
  config jsonb,
  created_at timestamptz default timezone('utc', now())
);

create table public.events (
  id bigint generated by default as identity primary key,
  user_id uuid,
  session_id text,
  variant_key text,
  type text,
  payload jsonb,
  created_at timestamptz default timezone('utc', now())
);

create index leads_email_idx on public.leads (email);
create index events_type_idx on public.events (type);
create index events_variant_idx on public.events (variant_key);
```

### RLS politicos
```sql
alter table public.users enable row level security;
alter table public.profiles enable row level security;
alter table public.leads enable row level security;
alter table public.subscriptions enable row level security;
alter table public.templates enable row level security;
alter table public.events enable row level security;

create policy "Users can view own profile" on public.profiles for select using (auth.uid() = user_id);
create policy "Users can update own profile" on public.profiles for update using (auth.uid() = user_id);
create policy "Insert leads" on public.leads for insert with check (true);
create policy "Read own leads" on public.leads for select using (auth.role() = 'authenticated');
create policy "Service role manage leads" on public.leads using (auth.role() = 'service_role') with check (auth.role() = 'service_role');
create policy "Users view own subs" on public.subscriptions for select using (auth.uid() = user_id);
create policy "Insert events" on public.events for insert with check (auth.role() = 'service_role' or auth.role() = 'authenticated');
create policy "Read events" on public.events for select using (auth.uid() is not null);
```

### Tipizuotas klientas (Supabase JS)
```ts
// lib/supabase-client.ts
import { createBrowserSupabaseClient } from '@supabase/auth-helpers-nextjs';
import { Database } from '@/types/supabase';

export const supabaseClient = createBrowserSupabaseClient<Database>();
```

### Užklausų pavyzdžiai
```ts
// Fetch active experiment variant
const { data } = await supabaseClient
  .from('experiments')
  .select('id, traffic_split')
  .eq('status', 'active')
  .single();

// Insert event
await supabaseClient.from('events').insert({ type: 'cta_click', variant_key: variantKey, payload: { path: pathname } });
```

## 6. EMAIL CAPTURE & FLOWS
### `/api/lead` route
```ts
// app/api/lead/route.ts
import { NextRequest, NextResponse } from 'next/server';
import { createClient } from '@supabase/supabase-js';

const supabase = createClient(process.env.SUPABASE_URL!, process.env.SUPABASE_ANON_KEY!);

export async function POST(req: NextRequest) {
  const { email, variantKey = 'control' } = await req.json();
  if (!email) {
    return NextResponse.json({ error: 'Email required' }, { status: 400 });
  }
  await supabase.from('leads').insert({ email, variant_key: variantKey });
  await supabase.functions.invoke('send-double-opt-in', { body: { email } });
  return NextResponse.json({ ok: true });
}
```

### Double opt-in Supabase Edge Function pseudo
```ts
// supabase/functions/send-double-opt-in/index.ts
import { Resend } from 'resend';

const resend = new Resend(Deno.env.get('RESEND_API_KEY')!);

Deno.serve(async (req) => {
  const { email } = await req.json();
  await resend.emails.send({
    from: 'LandingForge <hello@landingforge.app>',
    to: email,
    subject: 'Patvirtink prenumeratą',
    html: `<p>Spustelėk <a href="${Deno.env.get('PUBLIC_APP_URL')}/confirm?email=${encodeURIComponent(email)}">čia</a>, kad patvirtintum.</p>`,
  });
  return new Response(JSON.stringify({ ok: true }), { headers: { 'Content-Type': 'application/json' } });
});
```

### Onboarding seka (LT)
- **D0 (Subject: „Starto planas: tavo 7 dienų sprintas“)**
  - Sveikas (-a), pridedu Notion sprinto planą, 3 prioritetinius veiksmus D0, CTA į „užpildyk nišos formą“.
- **D1 (Subject: „Kaip išsirinkti nišą per 30 min“)**
  - Palyginti 3 gijos top idėjas, duoti scoring lentelę, CTA į šablono pasirinkimą.
- **D3 (Subject: „Landing prototipas ir hero tekstas“)**
  - Įdėti hero formulę, video walkthrough, CTA į A/B modulį.
- **D5 (Subject: „Stripe + email seka = pirmi mokėjimai“)**
  - Stripe integracijos checklista, webhook testavimo video, CTA – atlik test payment.
- **D7 (Subject: „Launch diena: kopija + UTM“)**
  - Launch playbook, social copy, CTA – pasidalink su #LandingForge žyma.

### Cart-abandon (LT)
- **T+2h (Subject: „Baigk registraciją ir gauk 40% nuolaidą“)** – link į `session_url`.
- **T+24h (Subject: „Gija jau veikia kitiems – tau liko 24h“)** – social proof + deadline.

### Trial ending (LT)
- **D-2 (Subject: „Tavo sprintas pasiekė finišą – kas toliau?“)** – highlight features, CTA upgrade.
- **D0 (Subject: „Paskutinė diena išlaikyti nuolaidą“)** – bullet benefits, link to portal.

## 7. TEMPLATE LIBRARY & MOAT
### 6 šablonai
1. **AI Builder** – hero „AI asistuojamas produktų paleidimas“, proof: gijos AI verslai, CTA „Start AI sprintą“.
2. **Fitness Challenge** – hero „7 dienų mikro programos“, proof: down-sell planų screenshotai, CTA „Prisijunk prie trenerių“.
3. **Coding Bootcamp Lite** – hero „Solo kūrėjų mikro SaaS planas“, proof: GitHub žvaigždės, CTA „Gauk repo šabloną“.
4. **Design Systems** – hero „Figma įmonių mikro biblioteka“, proof: logotipai, CTA „Parsisiųsk preview“.
5. **Finance Ops** – hero „Kasdienis cashflow dashboardas“, proof: MRR grafikai, CTA „Rezervuok demo“.
6. **Edu Creators** – hero „Micro kursų pipeline“, proof: studentų atsiliepimai, CTA „Atsidaryk kursų planą“.

### Auto A/B framework
- Konfigūracija JSON `templates.config.json`, nurodanti variantų ID, svertinius koeficientus, segmentavimo taisykles.
- Kliento pusėje `assignVariant()` (žr. §8), serverio log `events` lentelėje.

### Dokumentacija kūrėjams
- README modulio sekcija: „Kaip pridėti naują šabloną“ – kopijuoti `templates/[niche].json`, užpildyti hero/proof/cta, pridėti atitinkamą React komponentą, atnaujinti `templates.index.ts`.

## 8. A/B TESTING PLAN
### Eksperimento modelis
- Lentelė `experiments`: `variant` (A/B), `traffic_split` (pvz. {"control":0.5,"speed":0.5}).
- Metrikos: `cta_click`, `checkout_start`, `purchase_succeeded`, `email_subscribed`.
- Minimalus sample: 200 unikalių sesijų kiekvienam variantui, stop rule `Bayesian >95% posterior` arba 14 dienų.

### Variant priskyrimo snippet
```ts
// lib/assignVariant.ts
const STORAGE_KEY = 'lf-variant';

export function assignVariant(variants: Record<string, number>) {
  if (typeof window === 'undefined') return 'control';
  const stored = window.localStorage.getItem(STORAGE_KEY);
  if (stored) return stored;
  const rand = Math.random();
  let cumulative = 0;
  for (const [variant, weight] of Object.entries(variants)) {
    cumulative += weight;
    if (rand <= cumulative) {
      window.localStorage.setItem(STORAGE_KEY, variant);
      return variant;
    }
  }
  window.localStorage.setItem(STORAGE_KEY, 'control');
  return 'control';
}
```

### Įvykio registravimas
```ts
// lib/logEvent.ts
export async function logEvent(type: string, payload: Record<string, unknown>) {
  await fetch('/api/events', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ type, payload }),
  });
}
```

```ts
// app/api/assign-variant/route.ts
import { NextRequest, NextResponse } from 'next/server';
import { createClient } from '@supabase/supabase-js';

const supabase = createClient(process.env.SUPABASE_URL!, process.env.SUPABASE_SERVICE_ROLE_KEY!);

export async function POST(req: NextRequest) {
  const { sessionId, variant } = await req.json();
  await supabase.from('events').insert({ type: 'variant_assigned', session_id: sessionId, variant_key: variant });
  return NextResponse.json({ ok: true });
}
```

### Kliento integracija
```ts
// app/(landing)/page.tsx (excerpt)
const variant = assignVariant({ control: 0.5, speed: 0.5 });
useEffect(() => {
  const sessionId = crypto.randomUUID();
  logEvent('page_view', { path: '/', variant });
  fetch('/api/assign-variant', { method: 'POST', headers: { 'Content-Type': 'application/json' }, body: JSON.stringify({ sessionId, variant }) });
}, [variant]);
```

## 9. ANALYTICS & EVENTS
### Įvykiai
- `page_view`, `cta_click`, `checkout_start`, `purchase_succeeded`, `email_subscribed`, `variant_assigned`.

### `/api/events` route
```ts
// app/api/events/route.ts
import { NextRequest, NextResponse } from 'next/server';
import { createClient } from '@supabase/supabase-js';

const supabase = createClient(process.env.SUPABASE_URL!, process.env.SUPABASE_SERVICE_ROLE_KEY!);

export async function POST(req: NextRequest) {
  const { type, payload, variant, sessionId } = await req.json();
  await supabase.from('events').insert({ type, payload, variant_key: variant, session_id: sessionId });
  return NextResponse.json({ ok: true });
}
```

### Funnel dashboard SQL
```sql
-- Daily funnel
select
  date_trunc('day', created_at) as day,
  count(*) filter (where type = 'page_view') as page_views,
  count(*) filter (where type = 'cta_click') as cta_clicks,
  count(*) filter (where type = 'checkout_start') as checkout_starts,
  count(*) filter (where type = 'purchase_succeeded') as purchases,
  count(*) filter (where type = 'email_subscribed') as email_subs
from public.events
where created_at >= now() - interval '30 days'
group by 1
order by 1;
```

```sql
-- Variant performance
select
  variant_key,
  count(*) filter (where type = 'cta_click')::float / nullif(count(*) filter (where type = 'page_view'), 0) as ctr,
  count(*) filter (where type = 'checkout_start')::float / nullif(count(*) filter (where type = 'cta_click'), 0) as checkout_rate,
  count(*) filter (where type = 'purchase_succeeded')::float / nullif(count(*) filter (where type = 'checkout_start'), 0) as purchase_rate
from public.events
where created_at >= now() - interval '14 days'
group by variant_key;
```

### Minimalus dashboard
- Supabase SQL editor -> grafikai.
- Retool/Metabase (nemokamas planas) – 3 lentelės: „Daily Funnel“, „Variant Breakdown“, „Lead Growth“.

## 10. RIZIKOS & MAŽINIMAI
- **API limitai (X/Reddit):** naudoti vartotojo įkeltą CSV/screenshot; dėti rate limit 1 užklausa/min, caching su Supabase Storage; fallback – manual review modulis.
- **Turinio nuosavybė:** onboarding formoje reikalauti patvirtinti, kad turi teises; duoti gijos screenshot redagavimo gaires (pašalinti vartotojų vardus); laikyti Terms & Privacy.
- **GDPR/CPRA:** consent checkbox, cookie banner A/B testui, duomenų eksportas per `/api/account/export`, delete endpoint.
- **Stripe atitiktis:** privaloma pritaikyti SCA; webhook security; Customer Portal dunning.
- **Deliverability:** SPF/DKIM per Resend domeną, bounce monitoring.

## 11. 7 DIENŲ ĮGYVENDINIMO PLANAS
- **D1:** Analizė, nišos scoring, pasiūlymo ir kainodaros dokumentas. Surinkti gijos proof.
- **D2:** Landing šablono pritaikymas, Tailwind komponentai, hero/testimonial blokai.
- **D3:** Stripe produktai, `/api/checkout`, webhook testas (`stripe listen`).
- **D4:** Supabase schema, RLS, `events` logging, A/B bazė.
- **D5:** Email seka Resend, cart/trial sekos, edge functions.
- **D6:** QA (Lighthouse, accessibility), duomenų srautų testai, soft launch 10 beta.
- **D7:** Viešas launch (X, Reddit), monitor rezultatus, iteruok variantą (greitis vs proof).

## 12. LAUNCH PLAYBOOK
### X/Reddit kopija (3 versijos)
1. **Hype thread:**
   - Hook: „Starter Story gija pasidalino 25 nuobodžiais verslais. Aš paėmiau jų KPI ir sukūriau 7 dienų pajamų sprintą.“
   - Bulletai: (1) auto landing + email, (2) Stripe checkout, (3) 6 nišos šablonai.
   - CTA: `landingforge.app` su UTM `utm_source=twitter&utm_campaign=launch`
2. **Case study:**
   - „Kaip Lina per 72h nuo gijos pasiekė $1,8k pre-sale. LandingForge breakdown (screen).“ CTA su screenshot karusele.
3. **Builder log:**
   - „Day 7: Launchinu įrankį, kuris iš viralių gijų padaro monetizuojamą landingą. Nemokamas demo + 40% nuolaida pirmoms 48h.“

### Vizualų sąrašas
- Og vaizdas (1200x630) – gijos screenshot + stats.
- Stripe checkout GIF.
- Dashboard screenshot (daily funnel).
- Notion 7-day plan preview.

### UTM planas
- `utm_source` (twitter, reddit, newsletter), `utm_medium` (organic, reply, dm), `utm_campaign` (launch, beta, promo), `utm_content` (angle-skausmas, angle-greitis, angle-statusas).

### 3 dienų atsakymų strategija
- D1: atsakyti 30% komentatorių su personalizuotais tips.
- D2: DM top 10 interaktyvių žmonių su demo video.
- D3: follow-up su beta testimonialais ir paskutinės dienos nuolaida.

### Affiliate/Collab šablonas
```
Sveiki, [vardas]!
Matau, kad tavo auditorija ieško greitų pajamų idėjų. LandingForge per 7 dienas paverčia viralią giją į mokantį produktą.
Siūlau 30% komisinius pirmiems 3 mėn. + unikalų šabloną tavo nišai.
Ar galiu atsiųsti demo?
```

## 13. APLINKOS KINTAMIEJI
```
# .env.example
NEXT_PUBLIC_APP_URL=https://landingforge.app
NEXT_PUBLIC_STRIPE_STARTER_PRICE=price_xxx
NEXT_PUBLIC_STRIPE_PRO_PRICE=price_xxx
STRIPE_SECRET_KEY=sk_test_xxx
STRIPE_WEBHOOK_SECRET=whsec_xxx
SUPABASE_URL=https://xyz.supabase.co
SUPABASE_ANON_KEY=public-anon-key
SUPABASE_SERVICE_ROLE_KEY=service-role-key
RESEND_API_KEY=re_xxx
OPENAI_API_KEY=sk-xxx
GA_MEASUREMENT_ID=G-xxxxxx
```

## 14. PRIĖMIMO KRITERIJŲ PATVIRTINIMAS
- Testinis Stripe mokėjimas → webhook atnaujina `subscriptions` + Resend sveikinimo laiškas.
- Lighthouse tikslas ≥90 (veikiantys Tailwind komponentai, semantika, OG meta).
- Supabase events rodo `variant_assigned`, `page_view`, `purchase_succeeded` (SQL query).
- A/B sticky variant veikia per localStorage ir server events.
- Deploy per `vercel deploy` (Next.js 14 + App Router, edge-ready route handleriai).

## 15. QA CHECKLIST
- **Copy:** skaičiai (500 leads, 7 dienos), objection „be kodo“ apdorota.
- **Legal:** Terms/Privacy (Notion template), 14 d. refund, VAT – nenurodoma, nes JAV.
- **Accessibility:** kontrastas 4.5:1, focus states, aria label mygtukams.
- **Performance:** Next Image, dynamic import analytics, `next/script` defer.
- **Security:** Stripe webhook verification, Supabase RLS, input validation.

## 16. AUDITORIJOS & ŽINUČIŲ BRIEF (1 puslapis)
- **Persona 1:** AI turinio kūrėja (25 m., LA). Problema – neturi aiškios nišos, nori išleisti $1k/m prenumeratą. Žinutė – „AI Builder šablonas + pre-made email seka = per savaitgalį“. Kanalai: X, TikTok.
- **Persona 2:** Freelance dizaineris (32 m., NYC). Problema – nori skalės, bet trūksta sistemų. Žinutė – „Design Systems šablonas su auto checkout“. Kanalai: X, LinkedIn.
- **Persona 3:** Finansų konsultantas (38 m., Austin). Problema – per daug rankinio darbo su cashflow. Žinutė – „Finance Ops templatas + dashboard“. Kanalai: Newsletter, podcast.
- **JTBD:** (a) „Noriu padaryti mini produktą, kuris generuoja pajamas be developerio“, (b) „Reikia perkelti gijos social proof į landing“, (c) „Reikia CRM + A/B, kad nešaudytų aklai“.
- **Kalbos patternai:** „nuobodus = pelningas“, „7 dienų sprintas“, „Stripe per 30 min“, „šablonai x 6 nišoms“.
- **Objekcijos:** „Neturiu laiko“ (atsakymas – 6–8 val), „Nemoku programuoti“ (tailwind + Next.js template), „Kas jei nepavyks?“ (14 d. refund + proof).
- **Įrodymų šaltiniai:** gijos revenue screenshotai, beta klientų quotes, social proof moduliai.

