
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Instagram, Mail, Tiktok } from "lucide-react";

export default function Home() {
  return (
    <div className="p-4 grid gap-6">
      <header className="text-center">
        <h1 className="text-5xl font-bold italic" style={{ fontFamily: 'OisFont, cursive' }}>Ois Hills</h1>
        <p className="text-lg text-muted-foreground">Change your style, change your life</p>
      </header>

      <section className="grid grid-cols-1 md:grid-cols-3 gap-4">
        <Card>
          <CardContent className="p-4">
            <img src="/ois 3.jpg" alt="camiseta blanca" className="rounded-xl mb-2" />
            <p className="text-center italic">Taste of Love</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <img src="/ois 4.jpg" alt="camiseta negra" className="rounded-xl mb-2" />
            <p className="text-center italic">Do what you love</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <img src="/ois 5.jpg" alt="camiseta negra logo ois" className="rounded-xl mb-2" />
            <p className="text-center italic">Camiseta clásica Ois</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <img src="/ois 6.jpg" alt="camiseta verde Ois Hills" className="rounded-xl mb-2" />
            <p className="text-center italic">Estilo deportivo verde</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-4">
            <img src="/ois 8.jpg" alt="camiseta negra Ois Hills" className="rounded-xl mb-2" />
            <p className="text-center italic">Estilo deportivo negro</p>
          </CardContent>
        </Card>
      </section>

      <section className="text-center mt-10">
        <h2 className="text-2xl font-semibold mb-4">Casetas disponibles</h2>
        <p className="text-lg">Precio: $100.000 COP</p>
      </section>

      <footer className="text-center mt-10 border-t pt-4 space-y-2">
        <div className="flex justify-center gap-4">
          <a href="https://www.instagram.com/ois_hills" target="_blank" rel="noopener noreferrer">
            <Instagram className="w-5 h-5" />
          </a>
          <a href="https://www.tiktok.com/@oishills" target="_blank" rel="noopener noreferrer">
            <Tiktok className="w-5 h-5" />
          </a>
          <a href="mailto:Oishills17@gmail.com">
            <Mail className="w-5 h-5" />
          </a>
        </div>
        <p className="text-sm text-muted-foreground">© 2025 Ois Hills</p>
      </footer>
    </div>
  );
}


