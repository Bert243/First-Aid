import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import Image from "next/image";

export default function FirstAidGuide() {
  return (
    <div className="p-4 max-w-5xl mx-auto space-y-8">
      <header className="text-center space-y-2">
        <h1 className="text-4xl font-bold">First Aid Basics</h1>
        <p className="text-gray-600">Educational resource on what to do when medical help isn't immediately available</p>
      </header>

      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Why First Aid Matters</h2>
        <p>First aid saves lives. In emergencies where professional help isn’t nearby, knowing simple actions can help someone breathe, stop bleeding, or stay conscious until help arrives.</p>
      </section>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-4">
        <Card>
          <CardContent className="space-y-2">
            <Image src="/images/fractures.jpg" alt="Fractures first aid" width={400} height={250} className="rounded-2xl" />
            <h3 className="text-xl font-semibold">Fractures</h3>
            <ul className="list-disc list-inside text-gray-700">
              <li>Keep the injured limb still and supported.</li>
              <li>Apply a splint or sling if trained, to reduce movement.</li>
              <li>Seek medical help as soon as possible.</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2">
            <Image src="/images/heatstroke.jpg" alt="Heatstroke first aid" width={400} height={250} className="rounded-2xl" />
            <h3 className="text-xl font-semibold">Heatstroke</h3>
            <ul className="list-disc list-inside text-gray-700">
              <li>Move the person to a cool, shaded place.</li>
              <li>Remove excess clothing and use cool water or wet cloths to lower body temperature.</li>
              <li>Offer small sips of water if they are fully conscious.</li>
            </ul>
          </CardContent>
        </Card>
      </section>

      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">FAQ</h2>
        <p className="text-gray-700">Q: Should I always perform CPR on someone who isn't breathing?<br/>A: Only if the person is unresponsive and not breathing normally. Always call emergency services first.</p>
        <p className="text-gray-700">Q: Can I use any cloth for severe bleeding?<br/>A: Preferably a clean cloth or sterile dressing to reduce infection risk.</p>
      </section>

      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">About Us</h2>
        <p>We aim to educate the public on essential first aid practices that can help in critical moments. Our mission is to empower everyone with practical knowledge to act confidently during emergencies.</p>
      </section>

      <section className="space-y-4">
        <h2 className="text-2xl font-semibold">Contact</h2>
        <p>Have questions or want to request more guides? Email us at <a href="mailto:info@firstaidbasics.org" className="text-blue-600 underline">info@firstaidbasics.org</a>.</p>
      </section>

      <section className="text-sm text-gray-500 border-t pt-4">
        <p><strong>Disclaimer:</strong> This website is for educational purposes only and does not replace professional medical advice or care. Always seek trained medical assistance when possible.</p>
      </section>

      <footer className="text-center pt-4">
        <Button>Explore More Resources</Button>
      </footer>
    </div>
  );
}
