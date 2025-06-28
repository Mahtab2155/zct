import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

export default function HomePage() { return (

ZOON Charitable Trust Logo
ZOON CHARITABLE TRUST (Z.C.T)
Regd. 04-63-025 | Join Us Now

📧 zooncharitabletrust@gmail.com | 📞 7860671007

  <main className="p-4 grid gap-6 md:grid-cols-2">
    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">🔐 Self Registration</h2>
        <p className="text-sm mt-1">Users can register themselves online.</p>
        <Button className="mt-2">Register Now</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">📥 Download ID / Certificate</h2>
        <p className="text-sm mt-1">Get your official documents easily.</p>
        <Button className="mt-2">Download</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">📷 Media Gallery</h2>
        <p className="text-sm mt-1">Photos & YouTube videos from events.</p>
        <Button className="mt-2">View Gallery</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">💰 Donate to Support</h2>
        <p className="text-sm mt-1">QR code & Account info included.</p>
        <Button className="mt-2">Donate Now</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">📆 Upcoming Events</h2>
        <p className="text-sm mt-1">Get updates on future programs.</p>
        <Button className="mt-2">See Events</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">👥 Team & Verified Members</h2>
        <p className="text-sm mt-1">Meet the people behind Z.C.T.</p>
        <Button className="mt-2">View Team</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">📄 Upload Project / Certificate</h2>
        <p className="text-sm mt-1">Upload your work or docs directly.</p>
        <Button className="mt-2">Upload Now</Button>
      </CardContent>
    </Card>

    <Card>
      <CardContent>
        <h2 className="text-xl font-semibold">🧾 PDF Receipt for Donations</h2>
        <p className="text-sm mt-1">Get instant downloadable receipts.</p>
        <Button className="mt-2">Get Receipt</Button>
      </CardContent>
    </Card>
  </main>

  <footer className="text-center py-4 bg-yellow-100 text-sm mt-6">
    © {new Date().getFullYear()} ZOON Charitable Trust | Designed for community service
  </footer>
</div>
); }
